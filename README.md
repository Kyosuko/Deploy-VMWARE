# Deploy-VMWARE

Hi,

Having had a school automation project aimed at creating virtual machines thanks to PowerCLI through PowerShell, following this I would like to share my scripts with you:

- The script "Create Vm-v1.0" is the script to create several virtual machines from and with a confirmation at each creation of virtual machines.
- The script "Auto-Deploy-v1.0" is the script in the business partner case (deployment for customers Ex: OVH, FFG ...) with many functions:

  ! For all functions there are a check if PowerCLI is installed also when
  the script is launched and if not installed you receive a message which 
  say install withoption 18. Also a check if the values entered is correct 
  or nul and propose new entered. For function create and delete virtual 
  machine since csv filethere are check Power-cli, sendmail, powershell, 
  iso-file, datastore, datacenter it's depends of your choice with the 
  count of numbers parameters in csv file it'snot good you receive a 
  error message. There are yet many others options of verifications .. !

    * Create virtual machine                                     
    * Creation of virtual machines since a CSV file with the choice to import iso file then connect on   virtual machines and start all machines after creation
    * Create a folder for location virtual machines from vSphere 
    * Modify a value in a CSV file                               
    * Delete virtual machine                                     
    * Delete multiple virtual machines since a CSV file with the choice to stop all machines before deletion                
    * Start-up, shutdown and suspend a virtual machine           
    * Shutdown a virtual machine by power supply (Kill)          
    * Rename a virtual machine from vSphere                      
    * The search for the existence of a virtual machine          
    * Show the inventory (virtual machines, datastores, ...      
    * Install PowerCLI                                           
    * Get the last creation date of a virtual machine            
    * Import iso file in datacenter                              
    * Modify a value in a CSV file                               
    * Show the legend of color codes                              
    * Disconnect all active consoles connected to vSphere     

Both scripts have the ability to send success, error, cancellation and general report emails

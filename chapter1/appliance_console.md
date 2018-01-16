- appliance_console
- setup, configration using appliance_console
  with commands
- Issue: database disk - /dev/sdb
  (http://talk.manageiq.org/t/changing-the-default-database-to-dev-sdb/2495/4)\

##Get Started

Appliance Console is the command line ManageIQ configuration platform. To access ManageIQ configuration through this we need to start the appliance with using SSH key.

###Configuration setting
- Start the appliance with virtual manager and this opens a terminal console.
- We need to login through a SSH key i.e. the authentication credentials.
- This will login us to the VM with the previous login session details.
- We will enter "appliance_console" for menu options.

![Fig 1-Appliance_Console](https://cdn.pbrd.co/images/H34eWor.png "Fig 1(1.3) Appliance_Console")

- After entering the terminal we can see the summary information of the virtual manager.
- We can view menu or advanced settings to configure after clicking any key.
- We will get a list of 18 different options to configure ManageIQ. We just need to select the number associated with the item we wish to work on and furthur thing will be prompted by the console itself. This we will be studing here.

###Summary Information

Summary information states the current status of our ManageIQ virtual machine. Lets see some of them briefly.

![Fig 2-Summary Information](https://cdn.pbrd.co/images/H388DZH.png "Fig 2(1.3) Summary Information")

####Hostname
This is a hostname specified for the ManageIQ appliance. We can change this using advanced settings.

####IPV4 Address
This is a address which is used to access ManageIQ dashboard by a web browser. That we will be studing in 1.4 chapter.

####Timezone
It status the time zone which we prefer for our ManageIQ virtual machine. We will be studing it furthur.

####Local Database Server
It states that the local database server is running or not running currently.

####ManageIQ Server
The ManageIQ server status can be identified from this whether it is active or not.

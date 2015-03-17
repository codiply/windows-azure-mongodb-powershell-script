A PowerShell script that creates a Windows Azure Ubuntu virtual machine with a MongoDB Docker container deployed to it.

# Setup

* Make sure you have an account and you can login here [https://manage.windowsazure.com/](https://manage.windowsazure.com/).
* Install Windows PowerShell command-line tools from [http://www.windowsazure.com/en-us/downloads/](http://www.windowsazure.com/en-us/downloads/).
* Run PowerShell as Administrator.
* Run `Set-ExecutionPolicy RemoteSigned`.
* Run `Add-AzureAccount` and sign in on the screen that comes up.

# Run

Configure the parameters in `Example.ps1` and run `./Example.ps1` from the PowerShell window. Alternatively, type the contents of `Example.ps1` directly into the PowerShell window.

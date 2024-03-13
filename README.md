# Windows-Incident-Response-Kit
A Powershell script that will collect data from your Windows computer and save it to text files in a drive of your choice.

Run in an Administrative Powershell and watch the magic happen.

# What this will collect
  * Arp Table
  * Files a program has opened
  * Directories a program has opened
  * Running proccesses
  * Created and modified files from the last 24 hours
  * Event logs (Application, Security, System) entries from the last 24 hours
  * Startup apps
  * Installed software
  * Local accounts
  * Active directory accounts
  * Windows Defender information

# Background

During my last semester for my Cybersecurity and Network Administration course in college, one of my assigments was to make a windows response kit for my Network Security 2 class, where we had to write a powershell script that does all the things listed above. I am by no means a Powershell wizard, or a programmer.

# Credit:

Microsoft Learn

Bobcares Blog | Installed software portion | https://bobcares.com/blog/powershell-list-installed-software/

Lepide | local users portion | https://www.lepide.com/how-to/list-all-user-accounts-on-a-windows-system-using-powershell.html#:~:text=The%20Get%2DLocalUser%20PowerShell%20cmdlet,t%20have%20local%20user%20accounts.&text=Running%20the%20cmdlet%20without%20any,information%20about%20a%20specific%20account

Next Of Windows | Startup apps portion | https://www.nextofwindows.com/how-to-find-out-windows-startup-programs-in-powershell

Trinitrotolune & LReeder14 at Stack Overflow | Modified files portion | https://stackoverflow.com/questions/17366675/using-get-childitem-to-get-a-list-of-files-modified-in-the-last-3-days

ChatGPT | Code cleanup and housekeeping

Feel free to use this for whatever you'd like. If you're doing an article or something just credit me like normal.

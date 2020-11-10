# Sublime Text 3 - User Directory
These are my settings and packages that I have installed for my personal use, if you find them useful, feel free to use them for yourself. If you wish to see my Sublime Text 3 settings you can [click here](https://github.com/guitaristtom/sublimemergesettings).

### Pre-installation

Follow this guide on how to get Sublime Text 3 up and running on your system


Once you have ST3 running, you'll need to install Package Control
    [https://packagecontrol.io/installation](https://packagecontrol.io/installation)

Restart Sublime, and see if Package Control was successfully installed by opening the "Preferences" drop down and see if `Package Control` is showing under there.

### Installation
Make sure before you continue, that you have closed Sublime

#### Mac OS X / macOS
##### Using GIT
Open a Terminal and run these commands

    <TBA>

##### Direct Download
    <TBA>


#### Linux
##### Using GIT

    <TBA>

##### Direct Download

    <TBA>


#### Windows
##### Using GIT
Open a Command Prompt and run these commands

    cd %appdata%\"Sublime Text 3\Packages"
    rmdir User /s
    git clone <link above in "Clone or download"> User

##### Direct Download
  * Open a Windows "Run" prompt (Windows Key + R)
  * Put `%appdata%` in to open up your `Appdata\Roaming\` folder
  * Navigate to `Sublime Text 3` and then to `Packages` to open up your Sublime packages folder
  * Delete the `User` folder
  * Click the "Clone or download" button above, and download the ZIP file of this repo
  * Open the ZIP file, and extract the contents (not the first folder if there is one, go within that to where the bunch of files are) of it in to a new folder named "User"


### Post-Installation
Restart Sublime, you might have some errors pop up (especially if you don't have GIT installed).

Once you wait for all of the packages to install, restart Sublime and you should now be good to use my settings within Sublime

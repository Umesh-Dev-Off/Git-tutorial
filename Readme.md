

Timepass 

nstalling apps using apt is as easy as:

$ sudo apt install app_name
Uninstalling an app via apt is also super easy:

$ sudo apt remove app_name
To upgrade your installed apps, you'll first need to update the app repository:

$ sudo apt update
Once finished, you can update any apps that need updating with the following:

$ sudo apt upgrade
What if you want to update only a single app? No problem.

$ sudo apt update app_name
Finally, let's say the app you want to install is not available in the Debian repository, but it is available as a .deb download. You can install it manually using dpkg, the system that apt helps manage:

$ sudo dpkg -i app_name.deb
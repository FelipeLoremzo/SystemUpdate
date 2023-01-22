<h1>SystemUpdate</h1>
<h2>This script uses a series of commands to update and maintain a Debian-based Linux system.</h2>

For example;
- We use the "sudo apt update" command to update the package lists to make sure the packages are up to date;

- The "sudo apt upgrade -y" command upgrades all packages, using the -y flag to automatically confirm any prompts;

- "sudo apt dist-upgrade -y" upgrades packages, including those that require other packages to be removed or installed;

- "sudo apt autoremove -y" removes all packages that were installed as dependencies but are no longer needed;

- "sudo apt autoclean -y" cleans the package cache, removing all files that can no longer be downloaded and are not needed to restore any installed packages;

It's good practice to run these commands regularly to keep your system up-to-date and free of unnecessary files.

<h3>How to use</h3>

1 - Download the script https://github.com/FelipeLoremzo/SystemUpdate.git;

2 - Make the "system-update" script executable with "sudo chmod +x sistem-update.sh";

3 - Run the script with "sudo ./system-update.sh".

This script will update your package lists, update all packages, update packages that require other packages to be removed or installed, remove all packages that were installed as dependencies but are no longer needed, and clear the package cache.

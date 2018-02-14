# Clone Valet Site
Use command to clone valet installs

## Instructions
* Example code goes in terminal
```
cd ~
mkdir bin
cd bin
touch wp-clone
open -t wp-clone
```
Paste in the contents from the wp-clone file in this repository
Change the /Valet/ directory to you local Valet website folder if different
Save the wp-clone file
```
chmod +x wp-clone
```
Now you can run the following code to clone a site
```
wp-clone source-folder destination-folder
```

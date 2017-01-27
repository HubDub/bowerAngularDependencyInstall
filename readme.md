to install a new angular project from scratch, not copying someone else's bower.json file on Windows computer (must already have git & node.js)::

navigate where you want the project in Git terminal
mkdir initial project file & cd into it
mkdir lib folder & cd into it
open powershell terminal and cd into lib folder
in powershell type bower init and fill out form (this creates bower.json file)
in git terminal type bower install jquery --save (this downloads jquery and saves it to the bower.json file so others can copy your jason file and just type bower install to download all the dependencies)
in git terminal type bower install angular --save
in git terminal type bower install angular-route --save
you may have other angular dependencies you want to download depending on your project. for example, if you are working with firebase, type both bower install angularfire --save and bower install firebase --save

conversely, if you don't want to start from scratch, you can create your project folder, create the lib folder inside it, touch a bower.json file, then copy and paste the file with dependencies from another project. Then, in the command line simply type bower install and it will install the most recent version of the dependency. Even though though the bower.json file in the lib folder does not show the most recent version if you look inside the bower_components file, inside the angular folder, and find the bower.json, you'll see that it downloaded the most recent version regardless of what version you've typed into your json file. 

Note this is Angular, not Angular2. 
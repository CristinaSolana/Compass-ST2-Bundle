#Compass Sublime Text 2 Bundle

*Once finished, will include snippets for All Compass Core variables, mixins and functions + tab indexing for mixin and function parameters. Also, compass watch from withing ST2, see Build System below...*

**This is still a work in progress. Only a little less than half done in fact.**

---

### Sublime Text 2 Compass Core Snippets

Some day this will all make sense to others, but until then, just cryptic reminders for myself:

+ Parameter begins with $ = has default Compass variable 
+ int: integer
+ int+unit: integer + unit type, ex. 14px, 20%
+ booleen: true or false
+ mult_args: ability to add multiple arguments
+ ||&lt;del&gt;: if you do not want the available option, delete this parameter

---

### Sublime Text 2 Compass Build System

Big thanks to @nachtmeister for starting this script for Windows: https://github.com/WhatWeDo/Sublime-Text-2-Compass-Build-System and merging my Mac/Linux pull request: https://github.com/CristinaSolana/Sublime-Text-2-Compass-Build-System :)

Adds a Build System for Compass Watch when opening SASS Files. (Sublime-Text-2-SASS-Package or similar SASS Package needed. *Soon to be standalone*).

Create a project and place the Sublime Text Project file in your project's folder root.
Example:
yourproject/project.sublime-project

A Sublime Text 2 Project File in the root of your project is necessary.

#### Install


##### Prerequisites

Ruby and Compass have to be installed. 


##### Installation: Easy way

1. Open terminal / git bash and browse to the Sublime Text Packages Folder (OSX: cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages || WIN: C:\Users\<username>\AppData\Roaming\Sublime Text 2\Packages)

2. git clone git://github.com/WhatWeDo/Sublime-Text-2-Compass-Build-System.git Compass


##### Manually

1. Go to menu bar: "Sublime Text 2 > Preferences > Browse Packages..."
   - Alternate method, on OS X, in Terminal:
   - $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages

2. Once that folder is open, close Sublime Text 2.

3. Rename folder to Compass and move it in the package folder

4. Restart Sublime Text 2.


#### Build

Open one of your .sass files and press CTRL + B (or Tools > Build). If you have more than one Build System that is able to compile SASS, change the Build System to Compass under Tools > Build.

---

### TO-DO:


##### Snippets 
+ Finish CSS3: CSS Regions - User Interface
+ Layout
+ Reset
+ Typography
+ Utilities


##### Build System
+ Look into fix for RVM not playing nice with ST2. This error is not specific to this build system. It is specific to environments managing gems via rvm.


*Also, I suck at markdown.*
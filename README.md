# Compass Sublime Text 2 Bundle

##### What is it?

*Once finished, will include snippets for All Compass Core variables, mixins with tab indexing for parameters. Currently all of the CSS3 library is finished.

Also, adds a Build System for Compass Watch when opening SASS Files.

**This is still a work in progress. Thanks in advance for any input.**

---

## Install

#### Prerequisites, must be installed:

- Git (for installation of bundle)
- Ruby (for SASS + Compass)
- SASS (for Compass)
- Compass (errrr, that's what you're here for isn't it?)

#### Install from CMD Prompt (WIN) or Terminal (Linux/Mac)

1. Open terminal and browse to the Sublime Text Packages Folder 
Sublime Text 2
(OSX: cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages || WIN: C:\Users\<username>\AppData\Roaming\Sublime Text 2\Packages)
Sublime Text 3
(OSX: cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages || WIN: C:\Users\<username>\AppData\Roaming\Sublime Text 2\3\Packages)

2. git clone git@github.com:CristinaSolana/Compass-ST2-Bundle.git Compass

3. cd Compass

4. git submodule update --init (A must - to use Build System)

---

## Usage

#### Snippets

1. Easy: start typing the name of the Compass lib you are trying to access mixins for. (ex. background, border, etc)

Note: in some instances, I'v e included important notes about a mixin. I've made it a tab so that it can easily be deleted once selected via tab.

Some terminology:
+ unitless: unitless integer (ex. 1)
+ unit: integer + unit type (ex. 14px, 20%)
+ <some-param>:true||false - choose/type either true or false
+ ||&lt;del&gt;: if you do not want the available option, delete this parameter

---

#### Build System

Create a project and place the Sublime Text Project file in your project's folder root.
Example:
yourproject/project.sublime-project

Note: A Sublime Text 2 Project File in the root of your project is necessary.

Open one of your .sass files and press CTRL + B (or Tools > Build). 
Note: If you have more than one Build System that is able to compile SASS, change the Build System to Compass under Tools > Build.

Big thanks to @nachtmeister for starting this script for Windows: https://github.com/WhatWeDo/Sublime-Text-2-Compass-Build-System and merging my Mac/Linux pull request: https://github.com/CristinaSolana/Sublime-Text-2-Compass-Build-System :)

---

### TO-DO:

##### Snippets for: 
+ Layout
+ Reset
+ Typography
+ Utilities

##### Build System
+ Look into fix for RVM not playing nice with ST2. This error is not specific to this build system. It is specific to environments managing gems via rvm.

---

This package is licensed MIT.

# ts3up
**ts3up** is a little helper tool to automate a Teamspeak3-Server update on a 64bit linux-system.
The current developer version is *0.1.0*
With time there will be more features until the final version will be released.

# Installation

 1. Download the **ts3up** project
 2. Unzip it
 3. ```cd ts3up-master```
 4. ```chmod +x install```
 5. ```./install```
 
 ### Uninstall
 - ```rm /usr/local/bin/ts3up```
 
# Usage
### Syntax:

    ts3up [OPTION] argument

 ### Options:
  
  *-v \<versionnumber\>* 
  
Update server to <versionnumber>. By default it takes the current version"

 *-p \<path\>* 
 
 Set the path where the ts3-server files are. By default it the current directory"
 
 *-h*
 
 Displays the usage of the tool

### Example:
Update Teamspeak-server to version 3.12.1:

    ts3up -v 3.12.1    

Update Teamspeak-server to version 3.11.0 in path ~/teamspeak_files/

    ts3up -v 3.11.0 -h ~/teamspeak_files/

# Developer

 - Toni Wirth [toniwirth@icloud.com]

# License
MIT License

Copyright (c) 2020 toniwth

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

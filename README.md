# <Applescripts>

## My Applescripts

The first project in this repository is a short script used to look at a string and return a report of which characters are part of a hashtag (starting the index at character 1). This script was developed to be used as part of a larger script that allowed the graphic design department of a print company where I used to work to copy and paste a caption into an artwork template, and then change the text formatting of each character that was part of a hashtag so that it would appear as a clikable hyperlink on a print file. This was my first time attempting to analyze data within a string, and fortunately this project has not failed to deliver the desired result to me despite being fed all sorts of input strings from random customers.

The 2nd Project is a simple script to open the terminal and perform keystrokes to update the coursework supplied by Georgia Tech in their bootcamp program 

Other projects done in Applescript will be included as they are developed. 

## Installation

### Hashtag App

Any computer running MacOs that supports Applescript should execute the script without issue.

### Git Pull App

This also runs out of script editor, but will require that you open your Mac's preferences and give full access to Script Editor so that it may enter keystrokes into the terminal.

## Usage

For both scripts, and Applescript in general, you can open the files in script editor and then go to 

```
file >> export as
```
And then export as a read only application to launch the script with a double click on an icon. For any script that implements keystrokes, you'll also have to give the exported Application permission to access system events in the privacy settings of your Mac's settings first.
### Hashtag App

Simply run the script in the application "Script Editor", paste an input string into the text field of the dialog box that pops up and get the reults in the "results" field of the script editor window. 

![screenshot of input](./reamescreenshot_1.png)
![screenshot of output](./reamescreenshot_2.png)

### Git Pull App

if you have your course materials on your desktop, you just run the script. If you are not part of the GA Tech Bootcamp, you may have to edit line # 10 between the double quotes to the name of your class directory

### New Project App

If you are creating a new web page, you'll need to create a folder to house the site locally as you code it. You'll either be working in a repository clone or a locally created folder. You'll need an index.html page, a stylesheet, a script sheet, and the various folder structure to support the project. It can be tiresome to create all of this structure every time you start a new project so this Applescript lets you do it just by running a script. You can use this to create your starting folder locally, or to get started in a BLANK gitHub repo clone with only a README file. NOTE: you'll need to modify the code on line 9 of the code where the variable "truncatedProjectLocation" is defined. The "29" on that line is picking a place in the file path where terminal starts to have root access. It is omitting the following 28 characters on my computer
/Macintosh HD/users/Rowe2ry/ 

If your username is longer or shorty than "Rowe2ry" (7 characters) you'll need to modify that number "29" to +/- the difference in character length of your username to mine (Rowe2ry)
## Credits

I'd like to thank Advanced Color Imaging, a large format print shop in Norcross, GA for the tutelage in Applescript. It was in the midsts of a
9 year career with the shop that I learned everything I know about writing in Applescript as I developed the scripts to automate tasks on that job. The owners, Michael and Teresa Bash are, a huge part of my professional journey into writing code.

[Advanced Color Imaging](https://acibigcolor.com)

## License

MIT
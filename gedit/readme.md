# gedit Vray Scene Syntax Highlighter  #
**Version 1.0** Released January 19, 2015  
by Andrew Hazelden  

![This is a sample vray scene file with syntax highlighting](screenshots/gedit-vray-highlighter.png)

## Overview ##
I would like to present a new gedit syntax highlighting module that works with code from [Chaos Group's Vray Renderer](http://www.chaosgroup.com). The new modules make it easier for a VFX artist or technical director to edit a Vray vrscene file.

**Note:** The opens source program gedit is required to use the syntax highlighter. The gedit text editor is available for Linux, Windows, and Mac OS X systems.

## Download ##

The Vray Scene Syntax Highlighter module is a free download.

You can download the latest version on GitHub here:   
[https://github.com/AndrewHazelden/Vray-Scene-Syntax-Highlighter/](https://github.com/AndrewHazelden/Vray-Scene-Syntax-Highlighter/)

## Installation ##

**Step 1.**  [Download gedit](https://projects.gnome.org/gedit/) and install it on your system. If you are on Linux you already have a copy of gedit on you system. After you start gedit you will see a blank text editing window.


**Step 2.**  Copy the **Vray-Scene.lang** file to your gedit language-specs folder.

![Open the language-specs folder](screenshots/gedit-vray-folder.png)

On Windows you need to copy the Vray-Scene.lang file to the **language-specs** folder located at:
    `C:\Program Files (x86)\gedit\share\gtksourceview-2.0\language-specs\Vray-Scene.lang`  
or  
    `C:\Program Files\gedit\share\gtksourceview-2.0\language-specs\Vray-Scene.lang`  
  
On Linux you need to copy the Vray-Scene.lang file to the language-specs folder located at:
     `/usr/local/share/gtksourceview-2.0/language-specs/Vray-Scene.lang`  
or  
     `/usr/share/gtksourceview-2.0/language-specs/Vray-Scene.lang`  

     
**Step 3.**  We need to restart gedit for the new language module to be listed in the gedit **Highlighter Mode** menu. Let's check if the script was installed correctly by opening the menu **View > Highlighter Mode > Scripts > Vray Scene**.

![Select the Vray-Scene Language](screenshots/gedit-vray-highlight-mode.png)

If you open a Vray Scene (.vrscene) file at this point you will see formatted text. If you are working on an  Vray Scene file without the .vrscene extension you can select the language manually.


Let's manually enable the Vray Scene compatible syntax highlighting module. Open the **Language** menu on the bottom right of the window and select **Vray Scene**. This will turn on syntax highlighting and make it easier to develop complex Vray Scene files.
 
![Select the Vray Scene Language](screenshots/gedit-vray-languages-menu.png)

## Color Schemes ##
If you are new to gedit you will probably want to pick a color scheme to customize your work environment. You can switch the current color scheme by opening the **Edit** menu, and selecting **Preferences**. In the gedit Preferences window, click on the **Font & Colors** tab.

Clicking on the color scheme's name with switch between the different syntax highlighting color styles.

![Choose a Gedit Color Scheme](screenshots/gedit-color-schemes.png)

## Color Scheme Gallery ##

Gedit comes with 5 colors schemes by default:  

- Classic
- Cobalt
- kate
- Oblivion
- Tango

![Classic Color Scheme](screenshots/gedit-classic.png)
![Cobalt Color Scheme](screenshots/gedit-cobalt.png)
![Kate Color Scheme](screenshots/gedit-kate.png)
![Oblivion Color Scheme](screenshots/gedit-oblivion.png)
![Tango Color Scheme](screenshots/gedit-tango.png)

* * *

I hope the Vray Scene syntax highlighter improves your coding workflow as you develop and edit Vray Scene (.vrscene) files using the excellent gedit text editor. I've also created a Vray Scene syntax highlighter for Notepad++, BBEdit, and TextWrangler.

Cheers,    
Andrew Hazelden

Email: [andrew@andrewhazelden.com](mailto:andrew@andrewhazelden.com)   
Blog: [http://www.andrewhazelden.com](http://www.andrewhazelden.com)  
Twitter: [@andrewhazelden](https://twitter.com/andrewhazelden)  
Google+: [https://plus.google.com/+AndrewHazelden](https://plus.google.com/+AndrewHazelden)

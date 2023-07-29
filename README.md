

# GNU Image Manipulation Program
#### 2.99 Development Branch


> <b><u>Disclaimer:</u><b>
> 
>This is an unstable development release, an intermediate state on the
>way to the next stable release: GIMP 3.0. GIMP 2.99 may or may not do
>what you expect. Save your work early and often. If you want a stable
>version, please use GIMP 2.10 instead.
>
><b><u>Found a bug?</u><b>
>
>Please make sure that it hasn't been reported earlier and that it is not
>just new stuff that is still being worked on and obviously not quite finished yet.
>
> <b><u>Newcomers:</u><b>
> 
>If you want to hack on GIMP, please read the file devel-docs/README.md.
>For detailed installation instructions, see the file INSTALL.
## 1. Web Resources
<details open>
<summary>see more </summary>
<b><u>GIMP's home page:</u><b>
* https://www.gimp.org/

> Please be sure to visit this site for information, documentation,
tutorials, news, etc.  All things GIMP-ish are available from there.

<b><u>Latest version of GIMP:</u><b>
* https://www.gimp.org/downloads/
</details>

## 1. Web Resources
<b><u>GIMP's home page:</u><b>
* https://www.gimp.org/

> Please be sure to visit this site for information, documentation,
tutorials, news, etc.  All things GIMP-ish are available from there.

<b><u>Latest version of GIMP:</u><b>
* https://www.gimp.org/downloads/


## 2. Contributing
<b><u>GIMP source code can be found at:</u><b>

* GitLab:   https://gitlab.gnome.org/GNOME/gimp/
* GitHub: https://github.com/GNOME/gimp

<b><u>Resources for contributors:</u><b>
* https://developer.gimp.org/

In particular, you may want to look in the "Core Development" section. 

<b><u>Newcomers</u></b> (Some articles of interest):
* Setting up your developer environment: https://developer.gimp.org/core/setup/
* GIMP Coding Style: https://developer.gimp.org/core/coding_style/
* Submit your first patch: https://developer.gimp.org/core/submit-patch/


## 3. Discussion Channels

 <b><u>Discussion channels dedicated to GIMP user and development discussion: </b></u>
https://www.gimp.org/discuss.html

Several mailing lists archives are included in that page.
>
><b>Including: </b>
>* Gimp-user-list mailing list dedicated to user problems, hints and tips, discussion of cool effects, etc.  
>* Gimp-developer-list is oriented to GIMP core and plug-in developers.  
>* Gimp-gui-list is for discussing about GIMP interface to improve user experience. 
>
> Other discussion channels can be listed on this page when they are moderated by a team member, such as forums.

 <b><u>IRC channels devoted to GIMP. </u></b>
On <b>GIMPNet </b> (a private free software oriented network) there is #gimp. 
Many of the developers hang out there. 

<b><u>Some GIMPNet servers: </u></b>
<center>
	
	irc.gimp.org:6667
	
	irc.us.gimp.org:6667
	
	irc.eu.gimp.org:6667
	
</center>


## 4. Customizing GIMP
The look of GIMP's interface can be customized like any other GTK+ app.

Editing files in `${XDG_CONFIG_HOME}/gtk-3.0/` (settings.ini and gtk.css in particular) 
or by using "themes" (ready-made customizations).

Additionally, GIMP reads `${XDG_CONFIG_HOME}/GIMP/2.99/gimp.css` so you can have settings that only apply to GIMP.

You can also manually change the keybindings to any of your choice by editing: `${XDG_CONFIG_HOME}/GIMP/2.99/shortcutsrc`.


Have fun,

Spencer Kimball
Peter Mattis
Federico Mena
Manish Singh
Sven Neumann
Michael Natterer
Dave Neary
Martin Nordholts
Jehan



# GNU Image Manipulation Program   <sub><sup> 2.99 Development Branch</sup></sub>
> <b><u>Disclaimer:</u></b> 
>This is an unstable development release, an intermediate state on the
>way to the next stable release: GIMP 3.0. GIMP 2.99 may or may not do
>what you expect. Save your work early and often. 
>
>If you want a stable version, please use GIMP 2.10 instead.
>
><b><u>Found a bug?</u></b>
>Please make sure that it hasn't been reported earlier and that it is not
>just new stuff that is still being worked on and obviously not quite finished yet.
>
> <b><u>Newcomers:</u></b>
> See subsection 3 in this README for quicklinks.
>If you want to hack on GIMP, please read the additional [README](https://github.com/achidester/gimp/blob/master/devel-docs/README.md)
>For detailed installation instructions, see the file [INSTALL](https://github.com/GNOME/gimp/blob/master/INSTALL.in)
>
---
## 1. Web Resources
<b><u>GIMP's home page:</u><b>
* https://www.gimp.org/

> Please be sure to visit this site for information, documentation,
tutorials, news, etc.  All things GIMP-ish are available from there.

<b><u>Download GIMP latest version:</u><b>
* https://www.gimp.org/downloads/
---

## 2. Contributing
<b><u>GIMP source code can be found at:</u><b>
>
>* GitLab:   https://gitlab.gnome.org/GNOME/gimp/
>* GitHub: https://github.com/GNOME/gimp

<b><u>Resources for contributors:</u><b>
>* https://developer.gimp.org/
>
> In particular, you may want to look in the "Core Development" section. 

---

## 3. Newcomers: 
### Setting up your developer environment:
> The first step as a core developer is to build GIMP. 
> These pages contains all the resources necessary to set up your developer environment correctly.
> 
> * <a href="https://developer.gimp.org/core/setup/git/"> Obtaining source code </href>
> * <a href="https://developer.gimp.org/core/setup/build/"> Building GIMP  </href>
> * <a href="https://developer.gimp.org/core/setup/build-gimp-web/"> Building GIMP documentation  </href>
> 
### GIMP Coding Conventions:
>  This document describes the preferred coding style for the GIMP source code. 
>  It was originally inspired by [GNU’s coding style](https://www.gnu.org/prep/standards/standards.html#Writing-C) and developed from there across the years.
>  
> * <a href="https://developer.gimp.org/core/coding_style//"> GIMP coding style </href>
>
### Submitting your first patch:
> The GIMP project uses Gitlab’s [issue tracker](https://gitlab.gnome.org/GNOME/gimp/-/issues) to coordinate bug reports and contributed fixes. Gitlab is also used for enhancement requests and the preferred way to submit patches for GIMP is to make a [merge request](https://gitlab.gnome.org/GNOME/gimp/-/merge_requests) .
>  
> * <a href="https://developer.gimp.org/core/coding_style//"> GIMP coding style </href>
---

## 4. Discussion Channels

 <b>GIMP user and development discussion:</b>
> https://www.gimp.org/discuss.html
>
>Several mailing lists archives are included on this page.
>
><b>Including: </b>
>* Gimp-user-list mailing list dedicated to user problems, hints and tips, discussion of cool effects, etc.  
>* Gimp-developer-list is oriented to GIMP core and plug-in developers.  
>* Gimp-gui-list is for discussing about GIMP interface to improve user experience. 
>
> Other discussion channels can be listed on this page when they are moderated by a team member, such as forums.

<b><u>IRC servers via GIMPNet : </u></b>

>For the real junkies, there are IRC channels devoted to GIMP.
>On GIMPNet (a private free software oriented network) there is #gimp.
>Many of the developers hang out there. 
>
><b>Some GIMPNet servers:</b>
>* irc.gimp.org:6667
>*  irc.us.gimp.org:6667
>* irc.eu.gimp.org:6667
	
___


## 5. Customizing GIMP
>The look of GIMP's interface can be customized like any other GTK+ app.
>
> Editing files in `${XDG_CONFIG_HOME}/gtk-3.0/` (settings.ini and gtk.css in particular) 
> or by using "themes" (ready-made customizations).
>
> Additionally, GIMP reads `${XDG_CONFIG_HOME}/GIMP/2.99/gimp.css` so you can have settings that only apply to GIMP.
>
> You can also manually change the keybindings to any of your choice by editing: `${XDG_CONFIG_HOME}/GIMP/2.99/shortcutsrc`.

---
  <br />

Have fun, <br />
\-  Spencer Kimball  <br />
\-  Peter Mattis  <br />
\-  Federico Mena  <br />
\-  Manish Singh  <br />
\-  Sven Neumann  <br />
\-  Michael Natterer  <br />
\-  Dave Neary  <br />
\-  Martin Nordholts  <br />
\-  Jehan  <br />


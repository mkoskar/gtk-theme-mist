gtk-theme-mist
==============

:Description: Mist theme for gtk2/3
:License: GNU GPLv2 or later
:AUR: https://aur.archlinux.org/packages/gtk3-theme-mist-git/


gtk-2.0
-------

* uses Mist engine
* taken from Arch Linux gtk-engines 2.21.0-1 package
* no functional changes so far (just reformatted to sane style)


gtk-3.0
-------

* uses default gtk3 engine
* based on Mist-Redmond 1.2 (gtk3.8-theme_Mist-Redmond) taken from
  http://gnome-look.org/content/show.php?content=155580
* work in progress (goal is to match gtk2 version as closely as possible)

Known Issues (as of 03.01.2015 with gtk 3.14.6):

* focus hint
* text on progress bar
* visited links are white
* ComboBoxes: color under cursor should be white
* CheckBoxes, ComboBoxes: tick disappears
* Buttons: down state
* Buttons in dialogs
* FileChooser
* Tooltips
* Notebook, indent inactive tabs


Install
-------

Install like this::

    ~/.themes
    ~/.themes/Mist
    ~/.themes/Mist/gtk-3.0
    ~/.themes/Mist/gtk-3.0/widgets.css
    ~/.themes/Mist/gtk-3.0/colors.css
    ~/.themes/Mist/gtk-3.0/gtk.css
    ~/.themes/Mist/gtk-2.0
    ~/.themes/Mist/gtk-2.0/gtkrc

For GTK 2.x::

    $ cat ~/.gtkrc-2.0
    gtk-theme-name="Mist"
    ...

For GTK 3.x::

    $ cat ~/.config/gtk-3.0/settings.ini
    [Settings]
    gtk-theme-name=Mist
    ...

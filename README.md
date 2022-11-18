# Siemens PPCL User Defined Language

Siemens PPCL: User Defined Language for [Notepad++](https://notepad-plus-plus.org/).

## Installation

The easiest way to install is to use the User Defined Language GUI.
First download the `siemens-ppcl-udl.zip` file from the [releases page](https://github.com/mitchpaulus/siemens-ppcl-udl/releases).
Extract that zip file - inside will be the XML file `siemens-ppcl.xml`.
Using the menus in Notepad++, go to *Language > Define your language. .. > Import*.
Find the `siemens-ppcl.xml` you extracted and open that.

Close and restart Notepad++.
When you open it back up, you should see *Siemens PPCL* underneath *Define your language*.
Click that and you should see your file highlighted!

## Associated File Extension

I'm not sure that I've come across a global standard extension for these files.
I've chosen *.ppcl* to be the general extension for files in this language.
If the file ends with *.ppcl*, it should automatically be highlighted with the logic in this file.
If you prefer a different default extension, it is easy to change in the User Defined Language editor
(it's at the top to the right of the *Import...* and *Export* buttons).

## Color Scheme

The color scheme is based on 'londontube.light' from [terminal.sexy](https://terminal.sexy).
I chose this because it uses a pure white background, which most users of Notepad++ will be used to,
and I think it looks quite nice.

# QRC-Tools

Visual Studio Code extension, simplifying use of the QT Resource Collection Files (.qrc) by providing command interface.

> #### The extension is just starting to get created and planned - it does not work now (and won't for some time)

> #### This is NOT an official tool by the Qt Company

<br>

### Table of contents:

1. [QRC language configuration](#qrc-language-configuration)
2. [Add commands](#add-commands)
    - [**`Qrc: add this`**](#qrc-add-this)
    - [**`Qrc: add files`**](#qrc-add-files)
3. [Remove commands](#remove-commands)
    - [**`Qrc: remove this`**](#qrc-remove-this)
    - [**`Qrc: remove files`**](#qrc-remove-files)
4. [Look up commands](#look-up-commands)
    - [**`Qrc: look up this`**](#qrc-look-up-this)
    - [**`Qrc: look up this and go`**](#qrc-look-up-this-and-go)

<br>

# QRC language configuration

As QRC files are written in XML, they will be treated as such by vsc.

Additional support for QRC files isn't planned as my goal is to provide an interface for editing them.

Files with `.qrc` extension will receive an icon! 'Cause who does not love some colorfull shapes?  
The variant will be chosen based on vsc's theme.

(They will, at some point, be visible here)


<br>
<br>

# Add commands

<br>

## **`Qrc: add this`**

Adds currently opened file to .qrc file, chosen from dropdown.  
// GIF will be embeded here to provide usage example when the feature is implemented.

<br>

## **`Qrc: add files`**

Adds chosen files to selected .qrc file. Files will be picked in systems file explorer.  
// GIF will be embeded here to provide usage example when the feature is implemented.

<br>
<br>

# Remove commands

<br>

## **`Qrc: remove this`**

Removes currently opened file from *all* .qrc files. Modified .qrc files will be listed in a message.  
// GIF will be embeded here to provide usage example when the feature is implemented.

<br>

## **`Qrc: remove files`**
Removes selected files from *all* .qrc files. Files will be picked in systems file explorer.  
Modified .qrc files will be listed in a message.  
// GIF will be embeded here to provide usage example when the feature is implemented.

<br>
<br>

# Look up commands

<br>

## **`Qrc: look up this`**

Shows a message listing all .qrc files mentionning currently opened file.  
// GIF will be embeded here to provide usage example when the feature is implemented.

<br>

## **`Qrc: look up this and go`**

Jumps to a .qrc file mentioning currently opened file.  
As most files aren't included bymore than one .qrc file, no list depicting .qrc files will be provided.  
// GIF will be embeded here to provide usage example when the feature is implemented.



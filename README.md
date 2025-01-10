# Notepad++ SQF Syntax Highlighting and Auto Completion

Notepad++ syntax highlighting and autocompletion for SQF (the scripting language for the ArmA games).
All known functions from ArmA 3 (and previous titles) are supported. Code block folding is also supported.

## Installation


### Syntax Highlighting

1. Open the file "syntaxhighlighting/SQF.xml" and copy the contents.
2. Open the file "C:\Users\USERNAME\AppData\Roaming\Notepad++\userDefineLang.xml" and paste.
3. Restart Notepad++.

### Auto Completion

The steps in the section "Syntax Highlighting" are required for auto completion.

1. Copy the file "autocompletion/SQF.xml" into the folder "C:\Program Files (x86)\Notepad++\autoCompletion" (or where you installed Notepad++).
2. Restart Notepad++.
3. Open "Settings -> Preferences..." in Notepad++.
4. Go to the tab "Auto-Completion".
5. Choose following options:
  - Enable "Enable auto-completion on each input"
  - Choose "Function completion"
  - Set "From 3th character" (or what you prefer)

## How to modify styles

You can modify the styles via "Language -> Define your own Language". Select "SQF" (under "User language").

### Custom background color and font

Open "Settings -> Style Configurator". Set the background color and/or font under "Global Styles -> Default style".

### Themes

In the themes folder there are ready to use styles you can use instead of the default styles.
Open the "autocompletion/SQF.xml" and replace the "<Styles>...</Styles>" section with the content of one of the files in the themes folder.
After this, import your modified "autocompletion/SQF.xml" into Notepad++ (see section "Syntax Highlighting").
You may remove your existing styles first with "Language -> Define your own Language -> Remove".

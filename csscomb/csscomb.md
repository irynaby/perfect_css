# CSSCOMB

There is no special plugin for JetBrains' IDEs.
Instead, you can use CSScomb as an external tool:

## Installing

1. Install CSScomb: npm install csscomb
2. Go to Preferences > External Tools (or press ⌘, on Mac)
3. Click on Add icon (or press ⌘N on Mac)
4. Fill the form with following info:
– Name: CSScomb
– Program: path_to_installed_csscomb/bin/csscomb (see NB for Windows users below)
– Parameters: $FilePath$ -t
– Working directory: $FileDir$
All checkboxes in the form are optional, you can check whichever you want.
CSScomb will be available then in all menus you select.

NB. On Windows you may need to use npm config get prefix to get a directory with csscomb.cmd. So in "Program" field you will need to put something like C:\Users\User\AppData\Roaming\npm\csscomb.cmd.

5. Add .csscomb.json in your project's dir, or your HOME directory, or anywhere else.

[See docs](https://github.com/csscomb/csscomb.js/blob/master/doc/configuration.md#where-to-put-config) for info.

## Configure



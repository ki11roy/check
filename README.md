Runs `python -m py_compile` on your Python files, based on https://github.com/jbalogh/check

#### Installation

1) Make directory `c:\pycheck` and extract the archive there


#### Usage

Install TortoiseSVN hook (tsvn:precommithook)

1) Change directory to where your working copy is and run `install_hook.bat`

    chdir d:\src\my_working_copy
    c:\pycheck\install_hook.bat

   now your hook is in TortoiseSVN > Properties

2) Open `pycheck.py` and make sure that your Python's path is correct

3) From now on every time you commit your changes the dialog window should appear asking you 
   whether you want to apply the hook

Remove TortoiseSVN hook

1) Change directory to where your working copy is and run `remove_hook.bat`
 
    chdir d:\src\my_working_copy
    c:\pycheck\remove_hook.bat

#### Links

http://tortoisesvn.net/docs/release/TortoiseSVN_en/tsvn-dug-settings.html#tsvn-dug-settings-hooks
http://tortoisesvn.net/docs/release/TortoiseSVN_en/tsvn-dug-propertypage.html#tsvn-dug-propertypage-tsvn-props

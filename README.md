# jupyter-vsc-pymolpysnips (work in progress)
PyMOL Python snippet library to edit live Jupyter notebook cells with Visual Studio Code using [GhostText web browser extension](https://github.com/fregante/GhostText) and the [GhostText-for-Atom](https://github.com/GhostText/GhostText-for-Atom) plugin for Visual Studio Code. 

## On Windows 10 or 11

Store the `python.json` file in `\Users\\AppData\Roaming\Code\User\snippets\`. 
The folder `AppData` may be hidden if you use the Windows GUI to move the file. 
Instead, open the Command Prompt and use the `cmv` command to move the pml.json file into the snippets folder.

## On macOS    

Store the `python.json` file in ~/Library/Code/Application Support/Code/User/snippets/python.json.
If a `python.json` already exists, copy the contents between the external braces in the PyMOL `python.json` and paste inside the external braces of the original `python.json`.

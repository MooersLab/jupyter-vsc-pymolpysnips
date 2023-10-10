# jupyter-vsc-pymolpysnips

PyMOL Python snippet library to edit live Jupyter notebook cells with Visual Studio Code using [GhostText web browser extension](https://github.com/fregante/GhostText) and the [GhostText-for-VSCode](https://github.com/GhostText/GhostText-for-VSCode) plugin for Visual Studio Code. 
The snippets are formatted for the generic VSCode snippet format.
You may want to install the BioSyntax package for VSCode for color highlighting that is sensitive to biomolecular structure (e.g., recognizes PDB files).

## On Windows 10 or 11

Store the `source.python.json` file in `\Users\\AppData\Roaming\Code\User\snippets\`. 
The folder `AppData` may be hidden if you use the Windows GUI to move the file. 
Instead, open the Command Prompt and use the `cmv` command to move the `source.python.json` file into the snippets subfolder.

## On macOS    

Store the `source.python.json` file in `~/Library/Code/Application Support/Code/User/snippets/source.python.json`.
If a `source.python.json` file already exists, copy the contents between the external braces in the PyMOL `source.python.json` and paste inside the external braces of the original `source.python.json`.

## Note

Some snippets depend on some pymolshortcuts.
Add the [pymolshortcuts.py](https://github.com/MooersLab/pymolshortcuts) file to working working directory.

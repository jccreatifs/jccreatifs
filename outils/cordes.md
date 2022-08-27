# Remarques

## Linux Commands

### Update Alternatives
`sudo update-alternatives --install /usr/bin/cc cc /usr/bin/clang-15 100` \
`sudo update-alternatives --install /usr/bin/c++ c++ /usr/bin/clang++-15 100`  
 

### Installations
`sudo apt install clang-11 --install-suggests`


##Visual Studio Code

### Key BIndings
`{
    "key": "ctrl+`",
    "command": "workbench.action.terminal.focus"
},
{
    "key": "ctrl+`",
    "command": "workbench.action.focusActiveEditorGroup",
    "when": "terminalFocus"
}`

# vscode
Repo for my plugins vcscode 

How do I back uo my VS Code settings and list of installed extensions:
* Windows: %USERPROFILE%\.vscode\extensions
* Mac: ~/.vscode/extensions
* Linux: ~/.vscode/extensions

```
code --list-extensions  
code --list-extensions >> vs_code_extensions_list.txt  
cat vs_code_extensions_list.txt | xargs -n 1 code --install-extension  
code --list-extensions | xargs -n 1 code --uninstall-extension  
```

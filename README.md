### dot_files

Project created to store, synchorize and unify configs used accross different machines.



##### VSCode extensions
Dump: `code-oss --list-extensions > extensions.txt`
Sync: `cat extensions.txt | xargs -n 1 code-oss install-extension`



###### TODO:
- Add missing configs
- Clean .zshrc
- Add hooks to auto-sync things like vscode extensions

###### DREAM:
- Adapt to supported versions, like "work", "home", "server" etc.

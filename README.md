# Pixelbook  

### General Configuration
File search through Launcher ```chrome://flags/#enable-drive-search-in-app-launcher```
  
### Chrome Extensions Installed
[Nimbus - Screenshot Utility](https://chrome.google.com/webstore/detail/nimbus-screenshot-screen/bpconcjcammlapcogcnnelfmaeghhagj/related?hl=en)  
[uBlock Origin - Ad blocker](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm?hl=en)  
[1Password X - Password Manager](https://chrome.google.com/webstore/detail/1password-x-%E2%80%93-password-ma/aeblfdkhhhdcdjpifhhbdiojplfjncoa?hl=en)  
[Reddit Enhancement Suite](https://chrome.google.com/webstore/detail/reddit-enhancement-suite/kbmfpngjjgdllneeigpgjifpgocmfgmb?hl=en)  
  
### Crostini Setup and Configuration
Enable Linux support in Settings

### Crostini App Installation
#### VS Code
```
curl -L "https://go.microsoft.com/fwlink/?LinkID=760868" > vscode.deb
sudo apt install ./vscode.deb
```
Install Oh-My-Zsh, need to use patched files for prompt  
In settings.json need to update font info for both editor and terminal  
##### VS Code Extensions  
Bracket Pair Colorizer  
indent-rainbow  
Markdown All in One  
Material Icon Theme  
PowerShell  
Python  
### Python Environment
```
sudo apt-get install python3-pip

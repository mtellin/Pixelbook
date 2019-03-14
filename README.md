# Pixelbook  

### General Configuration
File search through Launcher ```chrome://flags/#enable-drive-search-in-app-launcher```  
Use newer Bluetooth ```chrome://flags/#newblue```  
This seems hit or miss, I still have an audio delay with both AirPods and QC35II  
  
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
Had issues getting VS Code to save GitHub username, easier to just clone repos via ssh (with key added to GitHub profile) vs https  
Install Oh-My-Zsh, need to use patched files for prompt  
In settings.json need to update font info for both editor and terminal  
### Postman

##### VS Code Extensions  
Bracket Pair Colorizer  
indent-rainbow  
Markdown All in One  
Material Icon Theme  
PowerShell  
Python  
Gist  
VS Live Share  
Settings Sync  
Prettier  
Go . 
### Python Environment
```
sudo apt-get install python3-pip
  
### Go Environment
Download latest from golang.org  
```
sudo tar -C /usr/local -xzf go1.10.3.linux-amd64.tar.gz
vi ~/.profile
```
And add the following at the end:  
```
# add golang to PATH
if [ -d "/usr/local/go/bin" ] ; then
        PATH="$PATH:/usr/local/go/bin"
fi
```
Then to apply changes immediately:  
```
source ~/.profile
```

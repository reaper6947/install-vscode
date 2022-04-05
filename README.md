# install-vscode
simple script to install vscode 
 first download the file to the local system by using these commands
 
 From `https://raw.githubusercontent.com/reaper6947/install-vscode/main/install-vscode.sh`:
```shell
curl -fsSL https://raw.githubusercontent.com/reaper6947/install-vscode/main/install-vscode.sh -o install-vscode.sh
chmod +x install-vscode.sh
sh install-vscode.sh
```
now install the required extentions for using ros and docker (not necessary if you only want to install vscode and nothing else)

```shell
sudo code --install-extension ms-iot.vscode-ros
sudo code --install-extension ms-azuretools.vscode-docker
```

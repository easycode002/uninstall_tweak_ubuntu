# uninstall_tweak_ubuntu

## 1-Uninstall GNOME Tweak Tool via Terminal
> 1-Uninstall GNOME Tweak Tool
```bash
sudo apt remove gnome-tweak-tool
```
> 2-Remove residual configuration files
```bash
sudo apt purge gnome-tweak-tool
```
> 3-Remove any unused dependencies
```
sudo apt autoremove
```

## 2-Remove GNOME Tweak Tool Configuration Files
> 1-Remove configuration files
```
rm -rf ~/.config/gnome-tweak-tool
```
> 2-Remove any related cache files
```
rm -rf ~/.cache/gnome-tweak-tool
```
> Update your machine
```
sudo apt update
```
> [!NOTE]
> To verify that GNOME Tweak Tool has been completely uninstalled from your Ubuntu system, you can perform the following checks
> Check if the Application is Still Accessible
```
gnome-tweaks
```
> Check the path of the executable
```
which gnome-tweakss
```

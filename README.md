# HAWT-Rotor Plymouth Theme

Animated plymouth theme with spinning horizontal-axis wind turbine (HAWT) rotor.

Modified from [vortex-ubuntu-plymouth-theme](https://github.com/emanuele-scarsella/hawt-rotor-plymouth-theme)

### Dependencies

* plymouth, libplymouth5, plymouth-label
* Recommended: plymouth-x11
* Install dependencies with `sudo apt install plymouth libplymouth5 plymouth-label`

### Boot up splash screen
![boot up splash screen](demo_boot.png)
### Shutdown splash screen
![shutdown splash screen](demo_shutdown.png)

# Installation

* go to the downloaded `hawt-rotor-plymouth-theme` folder from terminal, it can be done with the following command
```
cd /PATH/TO/hawt-rotor-plymouth-theme
```
or by opening the folder with your file explorer and going to RIGHT-CLICK > Open in Terminal
* make the `install` file executable, it can be done with the following command
```
sudo chmod +x install
```
* execute the `install` file, it can be done with the following command
```
sudo ./install
```

# Test

* go to the downloaded `hawt-rotor-plymouth-theme` folder from terminal, it can be done with the following command
```
cd /PATH/TO/hawt-rotor-plymouth-theme
```
or by opening the folder with your file explorer and going to RIGHT-CLICK > Open in Terminal
* make the `show-splash.sh` file executable, it can be done with the following command
```
sudo chmod +x show-splash.sh
```
* execute the `show-splash.sh` file, it can be done with the following command
```
sudo ./show-splash.sh
```

# Removal

* go to the downloaded `hawt-rotor-plymouth-theme` folder from terminal, it can be done with the following command
```
cd /PATH/TO/hawt-rotor-plymouth-theme
```
or by opening the folder with your file explorer and going to RIGHT-CLICK > Open in Terminal
* make the `uninstall` file executable, it can be done with the following command
```
sudo chmod +x uninstall
```
* execute the `uninstall` file, it can be done with the following command
```
sudo ./uninstall
```
* then when asked chose the new plymouth theme by typing the number of your choice and pressing `Enter`

# Customizing background color

* open the file in `hawt-rotor/bg.png` in any image editor of your choice

* fill the image with the color you want as background

* save changes ensuring NOT to change the file name `bg.png` or its location `hawt-rotor`

* proceed to installation/reinstallation

# Customizing background image

* rename, remove or move to a different folder the file in `hawt-rotor/bg.png`

* put your custom background image IN PNG FORMAT inside the `hawt-rotor` folder

* rename your custom beckground image as `bg.png`

* proceed to installation/reinstallation

## License

This project is licensed under the GPL v.2 License - see the LICENSE.md file for details
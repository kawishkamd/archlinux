i3 preview

![2024-08-04-12:06:54-screenshot](https://github.com/user-attachments/assets/7fedd9a4-18a8-42cf-8e80-27ebb3428c69)

![2024-08-03-19:53:10-screenshot](https://github.com/user-attachments/assets/5cbcb35b-bcb6-4349-9cee-8500ac1880d1)

sway preview
![2024-07-22_17-51-20](https://github.com/user-attachments/assets/00eeb721-dd8a-4168-9c6f-c7bacd577723)


## WIKI
1. GTK Theme installation
	
	- ```sudo pacman -S arc-gtk-theme```
	
	- ```mkdir ~/.config/gtk-3.0```
	
	- ```echo -e "[Settings]\ngtk-theme-name=Arc-Dark" > ~/.config/gtk-3.0/settings.ini```

2. AUR Helper Setup
	
	- ```sudo pacman -Syu git base-devel```
	
	- AUR Helpers
		-  ```git clone https://aur.archlinux.org/yay.git```
		-  ```git clone https://aur.archlinux.org/trizen.git``` (personal fav)
		-  ```git clone https://aur.archlinux.org/paru.git```
	 
	- clone the repo and cd in to the file
	
	- Run ```makepkg -si``` command without sudo.

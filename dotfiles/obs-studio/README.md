### OSB-INSTALL ON WAYLAND
OBS BLACK SCREEN FIX ON WAYLAND : SWAY

- sudo pacman -S obs-studio 
- sudo pacman -S pipewire pipewire-pulse wireplumber xdg-desktop-portal xdg-desktop-portal-wlr qt5-wayland
-
    systemctl --user start xdg-desktop-portal

    systemctl --user start xdg-desktop-portal-wlr

    systemctl --user enable xdg-desktop-portal

    systemctl --user enable xdg-desktop-portal-wlr

    systemctl --user start pipewire

    systemctl --user start wireplumber

    systemctl --user enable pipewire

    systemctl --user enable wireplumber

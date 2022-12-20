### GTK4 Discord client in Go - flatpak'd
Flatpak of https://github.com/diamondburned/gtkcord4

### How To
1. `git clone https://github.com/saori-yuko/com.github.diamondburned.gtkcord4.git`
2. `cd com.github.diamondburned.gtkcord4`
3. `flatpak install runtime/org.freedesktop.Sdk.Extension.golang/$(uname -m)/22.08 runtime/org.gnome.Sdk/$(uname -m)/43`
4. `flatpak-builder build com.github.diamondburned.gtkcord4.yml --install --user`

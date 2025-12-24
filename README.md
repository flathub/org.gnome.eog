# Eye of GNOME

___Browse and rotate images___

Eye of GNOME is an image viewer designed for the GNOME desktop. It integrates with the GTK look and feel of GNOME, and supports many image formats for viewing single images or images in a collection.

It also allows to view the images in a fullscreen slideshow mode or set an image as the desktop wallpaper. It reads the camera tags to automatically rotate your images in the correct portrait or landscape orientation.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```
flatpak install flathub org.gnome.eog
flatpak run org.gnome.eog
```

## Building

```
git clone git@github.com:flathub/org.gnome.eog.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install org.gnome.eog.yml
```

---

**Technologies**: GNOME, GTK3, Libhandy, C

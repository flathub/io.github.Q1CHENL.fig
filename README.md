# Fig

___Sleek GIF editor___

Fig is a simple and intuitive GIF editor that lets you edit GIFs with ease. 

- Crop, flip and rotate GIF
- Trim GIF to any frame range
- Reverse GIF
- Remove specific frames
- Insert GIF/image(s) at any position
- Change playback speed for specific frames
- Duplicate frame range
- Extract frames
- Export GIF as video
- Play GIF at the original speed
- Text embedding
- Draw on gif

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing

```
flatpak install flathub io.github.Q1CHENL.fig
flatpak run io.github.Q1CHENL.fig
```

## Building

```
git clone git@github.com:flathub/io.github.Q1CHENL.fig.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install io.github.Q1CHENL.fig.json
```

---

**Technologies**: GNOME, GTK4, Libadwaita, Python

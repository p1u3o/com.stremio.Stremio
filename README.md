# com.stremio.Stremio Flatpak
This builds Stremio as a Flatpak using sources. It only needs org.kde.Platform 5.12 to run.

You can fetch a prebuilt flatpak at https://github.com/p1u3o/com.stremio.Stremio/releases and install using 
```
flatpak install com.stremio.Stremio.flatpak
```

## Build
```
flatpak-builder --install  --install-deps-from=flathub _build com.stremio.Stremio.json --force-clean
```
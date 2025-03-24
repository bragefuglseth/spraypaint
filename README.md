<picture>
  <source srcset="./files/usr/share/pixmaps/fedora-logo-sprite.png" width="auto" height="128" media="(prefers-color-scheme: light)"/>
  <source srcset="./files/usr/share/pixmaps/system-logo-white.png" width="auto" height="128" media="(prefers-color-scheme: dark)"/>
  <img src="./files/usr/share/pixmaps/fedora-logo-sprite.png"/>
</picture>

# Spraypaint

A Fedora Silverblue variant with some light modifications, namely:

- Replacing Fedora Flatpaks with Flathub ones
- Installing the GNOME Core app set, with:
  - Decibels by default
  - Showtime replacing Totem
  - Papers replacing Evince
- Enabling the full GNOME wallpaper set
- Removing the Firefox system package

Use at your own discretion; I'm no expert at this.

## Usage

From an existing immutable system:

```
rpm-ostree rebase ostree-unverified-registry:ghcr.io/bragefuglseth/spraypaint:latest
```

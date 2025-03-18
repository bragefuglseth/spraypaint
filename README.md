# Spraypaint

A Fedora Silverblue variant with some light modifications, namely:

- Replacing Fedora Flatpaks with Flathub ones
- Installing the GNOME Core app set, with:
  - Decibels by default
  - Showtime replacing Totem
  - Papers replacing Evince
- Enabling the full GNOME wallpaper set
- Removing the Firefox system package

## Usage

From an existing immutable system:

```
rpm-ostree rebase ostree-unverified-registry:ghcr.io/bragefuglseth/spraypaint:latest
```

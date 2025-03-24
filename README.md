<picture>
  <source srcset="./files/usr/share/pixmaps/fedora-logo-sprite.png" width="auto" height="128" media="(prefers-color-scheme: light)"/>
  <source srcset="./files/usr/share/pixmaps/system-logo-white.png" width="auto" height="128" media="(prefers-color-scheme: dark)"/>
  <img src="./files/usr/share/pixmaps/fedora-logo-sprite.png"/>
</picture>

# Spraypaint

A general-purpose operating system, the way I think it should be.

Key characteristics:

- Powered by [Fedora Silverblue][silverblue]
- Unmodified [GNOME][gnome] environment with all core apps included by default
- [Flathub][flathub] as the one and only source of apps

Spraypaint has no versioning or release scheme, you simply start using it and receive automated updates on a daily basis or whenever I feel like making a change.

## Usage

From an existing immutable system:

```
rpm-ostree rebase ostree-unverified-registry:ghcr.io/bragefuglseth/spraypaint:latest
```

## Credits

Spraypaint is made possible by [Fedora][fedora] and [BlueBuild][bluebuild].

[silverblue]: https://fedoraproject.org/atomic-desktops/silverblue/
[gnome]: https://www.gnome.org/
[flathub]: https://flathub.org/
[fedora]: https://fedoraproject.org/
[bluebuild]: https://blue-build.org/

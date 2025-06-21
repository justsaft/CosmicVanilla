
# Sending Vanilla spice into space

> [!NOTE]
> Personal image. If you don't like any change, consider [https://github.com/Vanilla-OS/custom-image](https://github.com/Vanilla-OS/custom-image)

> [!WARNING]
> This is work in progress

Vanilla OS based custom image that uses Cosmic as its Desktop Environment.

Bases off of [Singularity OS](https://github.com/singularityos-lab/desktop-image).
Similarities are expected until things need to be patched etc.

Uses `vanilla-os/core:main` as the base image and pulls in a bunch of
non-desktop related modules from `vanilla-os/desktop` as remote modules.

Only the modules that needed to change or are new are located in `./modules`

Use `justsaft/cosmicvanilla` for the image name object in your abroot's config.
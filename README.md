# Flatpak build for Eden emulator

Unpacked from the official Appimage release.

Before build, install the runtime and SDK if it is not already installed:
flatpak install org.freedesktop.Platform/25.08 org.freedesktop.Sdk/25.08

Then build and install locally with:
flatpak-builder --install builddir --user --force-clean dev.eden_emu.eden.yml


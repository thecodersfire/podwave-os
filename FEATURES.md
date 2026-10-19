# Built-in features for podwave-os

Purpose: podcast production

1. **organize project files** — run podwave-os-workspace. It creates ~/Documents/podwave-os-workspace/ with Inbox, Projects, Archive folders.
2. **draft a session plan** — run podwave-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/podwave-os-session-plans/.
3. **check task readiness** — run podwave-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/podwave-os-workspace features/podwave-os-plan features/podwave-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for podcast production:

1. **Ardour** — org.ardour.Ardour
2. **Mixxx** — org.mixxx.Mixxx
3. **Inkscape** — org.inkscape.Inkscape

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for podcast production:

1. **VLC** — review media files (org.videolan.VLC)
2. **Kdenlive** — edit video timelines (org.kde.kdenlive)
3. **Blender** — create 3D assets and animations (org.blender.Blender)
4. **GNOME Sound Recorder** — capture voice and field notes (org.gnome.SoundRecorder)
5. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
6. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
7. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
8. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
9. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
10. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

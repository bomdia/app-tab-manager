# App Tabs

## Overview

**AppTabs** is a Gnome extension that allows your panel to include tabs for different windows of launched applications.

## Installation
Clone this repository and copy it to path `.local/share/gnome-shell/extensions/`

## DEBUG
Gnome Shell:
```bash
dbus-run-session -- gnome-shell --nested --wayland
```
Preferences:
```bash
journalctl -f -o cat /usr/bin/gjs
gnome-extensions prefs huanghaohhoa@163.com
```

## Feature
1. You can see the application window intuitively
2. Click tab to jump to the corresponding window immediately
3. Click the Close button to close the window

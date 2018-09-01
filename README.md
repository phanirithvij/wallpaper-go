# wallpaper-go

This is a cross-platform Go library and executable for modifying the desktop wallpaper

This expands on, and is based on code from, https://github.com/reujab/wallpaper

- Adds an executable command-line utility
- Enables setting of wallpaper fill styles (tile, stretch, fit, fill, etc)
- Leaves HTTP downloading out to keep a smaller interface

Mainly wanted this because dealing with the various Windows APIs via C/C++ is _awful_, especially for wallpapers. Looked around for alternatives and found the other project, and wanted to go a different direction with it.
# Fooyin_Config

---

**Description**:  
This repository contains a custom layout and preset for the **Fooyin Music Player**, inspired by the aesthetic of *Neon Genesis Evangelion*. The "Evangelion Theme (Sort Of)_5" configuration offers a visually appealing and functional setup for music enthusiasts, featuring a sleek interface with organized widgets, a detailed playlist view, and a custom theme. The repository includes the layout file (`.fyl`), a preset file (`.md`), and a README for setup instructions.

### Features
- **Custom Layout**: A thoughtfully designed interface with splitters, player controls, seek bar, volume controls, playlist, artwork panel, lyrics display, and more, as defined in `Evangelion Theme (Sort Of)_5.fyl`.
- **Preset Configuration**: A detailed preset (`Preset_Evangelion Theme (Sort Of)_5.md`) for the playlist view, including headers, subheaders, and track formatting with dynamic fields like album, artist, track count, and playtime.
- **Evangelion-Inspired Theme**: A visually striking theme encoded in the layout file, tailored for a unique and immersive music playback experience.
- **Responsive Design**: The layout is optimized for a window size of 1024x710 pixels, with flexible splitters for customization.

### Repository Structure
```
Layout
└── 'Evangelion Theme'
    ├── 'Evangelion Theme (Sort Of).fyl'
    ├── 'Evangelion Theme (Sort Of)_OverComplicated.fyl'
    ├── 'Preset_Evangelion Theme (Sort Of).md'
    ├── Preview
    │   ├── 82ac27a99ca5328fcefbbb21fa5a4afc.png
    │   ├── c0668b3974fcb030d3a9399453034e88.png
    │   ├── fda4c45fceeb2213415d5717c4fa43df.png
    │   └── OverComplicated
    │       ├── 2bf9992193896278ac69833b7f5f29c2.png
    │       ├── 76d0af97a48ca18fa3a7d178a06e55f6.png
    │       ├── ac724a556eaef692190b59b12f10df24.png
    │       └── c0a64010cf30188ccb2eb5058496c40c.png
    └── Preview.md
README.md
```

### Layout Details
The `Evangelion Theme (Sort Of)_5.fyl` file defines a comprehensive layout for Fooyin Music Player, featuring:
- **Widgets**: Includes PlayerControls, SeekBar, VolumeControls, PlaylistControls, ScrobbleToggle, SearchBar, LibraryFilter, ArtworkPanel, Playlist, Lyrics, PlaybackQueue, SelectionInfo, and StatusBar.
- **Splitter-Based Layout**: Uses nested vertical and horizontal splitters for flexible widget arrangement.
- **Library and Playlist**: Two LibraryFilter widgets with different column settings and a Playlist widget with custom columns (e.g., track number, title, artist, play count, duration).
- **Artwork and Lyrics**: Dedicated panels for album artwork and lyrics display, with options to maintain aspect ratio and align cover art.
- **Window Size**: Configured for 1024x710 pixels.

### Preset Details
The `Preset_Evangelion Theme (Sort Of)_5.md` file customizes the playlist view with:
- **Header**: Displays album title (or "Unknown Album") and album artist (or "Unknown Artist") with a cover image and 50-pixel height override.
- **Subheaders**: Shows disc number (for multi-disc albums) on the left and playtime on the right.
- **Tracks**: Formats track listings with queue indexes, track number, title, artist, play count, and duration, with indentation for hierarchical display.
- **Dynamic Formatting**: Uses Fooyin's scripting syntax (e.g., `$if2`, `$ifgreater`, `$padright`) for conditional and formatted text.

### Installation
1. **Download Fooyin Music Player**: Ensure you have Fooyin installed (available at [Fooyin GitHub](https://github.com/fooyin/fooyin)).
2. **Copy Layout File**: Place `Evangelion Theme (Sort Of)_5.fyl` in Fooyin's layout directory (refer to Fooyin's documentation for the exact path).
3. **Apply Preset**: Import `Preset_Evangelion Theme (Sort Of)_5.md` into Fooyin's playlist preset settings.
4. **Load Layout**: Open Fooyin, go to the layout settings, and load the `Evangelion Theme (Sort Of)_5.fyl` file.
5. **Enjoy**: Customize the layout further if desired, and enjoy the Evangelion-inspired music experience!

### Contributing
Feel free to fork this repository, modify the layout or preset, and submit pull requests with improvements or new themes. Issues and feature requests are welcome!


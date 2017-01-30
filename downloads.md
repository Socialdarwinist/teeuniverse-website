---
layout: default
title: Downloads
permalink: /downloads/
type: dataset
creator: necropotame
contentdescription: List of the TeeUniverse releases with version history, including links to compressed distributions of their source codes and their binaries
---

# TeeUniverse cutting edge (Experimental)

* [Source code (zip)](https://github.com/teeuniverse/teeuniverse/archive/master.zip)
* [Source code (zip)](https://github.com/teeuniverse/teeuniverse/archive/master.tar.gz)

# TeeUniverse 0.2.1 (Latest Release) #

* [Linux 32-bit binaries](https://github.com/teeuniverse/teeuniverse/releases/download/v0.2.1/teeuniverse-0.2.1-linux_x86.tar.gz)
* [Linux 64-bit binaries](https://github.com/teeuniverse/teeuniverse/releases/download/v0.2.1/teeuniverse-0.2.1-linux_x86_64.tar.gz)
* [Windows 32-bit binaries](https://github.com/teeuniverse/teeuniverse/releases/download/v0.2.1/teeuniverse-0.2.1-win32.zip)
* [Source code (zip)](https://github.com/teeuniverse/teeuniverse/archive/v0.2.1.zip)
* [Source code (tar.gz)](https://github.com/teeuniverse/teeuniverse/archive/v0.2.1.tar.gz)

## Change Log ##

### Added ### 
- Images can be replaced and exported
- Eraser tool for images
- Ability to change the group of a layer, using layer ordering or a dedicated button
- Ability to move a group in background/foreground using group ordering
- Button to duplicate groups, entity layers, zone layers and other map layers
- Button to set the zoom to 1:1
- Entry box to display and set the zoom factor
- Option to keep entities, quads and vertices align with the grid during translation
- Creation of quads when no images are defined in the layer

### Changed ### 
- Path creator tool create corner vertices by default
- Vertex smooth type is now visible directly in the list of vertices
- Updated infclass package

### Fixed ### 
- List of quads and entities is not updated after using the stamp tool
- Two Bezier controllers displayed on end points
- Two assets can have the same name, leading to corrupted TUP file
- Delete a layer in a map change the current edited element to none, leading to an empty view
- Incoherent behaviour of the right click in the asset list
- Mouse click in the map display settings pass through the popup window

# TeeUniverse 0.2.0 #

* [Linux 32-bit binaries](https://github.com/teeuniverse/teeuniverse/releases/download/v0.2.0/teeuniverse-0.2.0-linux_x86.tar.gz)
* [Linux 64-bit binaries](https://github.com/teeuniverse/teeuniverse/releases/download/v0.2.0/teeuniverse-0.2.0-linux_x86_64.tar.gz)
* [Windows 32-bit binaries](https://github.com/teeuniverse/teeuniverse/releases/download/v0.2.0/teeuniverse-0.2.0-win32.zip)
* [Source code (zip)](https://github.com/teeuniverse/teeuniverse/archive/v0.2.0.zip)
* [Source code (tar.gz)](https://github.com/teeuniverse/teeuniverse/archive/v0.2.0.tar.gz)

## Change Log ##

### Added ### 
- Object layers in maps
- Materials
- Tool to create sprite from images
- Tools to create an object and edit its vertices
- Mirror buttons for tile layers
- Export maps to the InfClass format
- Ctrl+Left button to move the camera in the map
- Shortcuts to flip and rotate the stamp selection
- Text selection with copy/paste
- Automatic scrolling during text editing
- Statusbar to display map coordinates
- Confirmation dialog during saving
- Ctrl+S to save the current package
- Import/Export in PTU map format
- Option to align entities with on the grid
- Camera position and zoom saved in the package
- Settings in map view
- Game layer of DDNet maps support

### Changed ### 
- Bigger toolbar in the view
- New icons for tools in the view
- Better appearance for focused boxes
- Better appearance for separators

### Removed ###
- Import/Export in the old InfClass map format

### Fixed ### 
- Fix non-loaded images after deletion of an image
- Fix unusable crop tool for map layers (the tool is now disabled for layers)
- Fix incoherent behaviour for sliders
- Fix visible gui_editor package in the asset selector
- Fix wrong clipping values for exported maps
- Fix internal images exported as external
- Fix env_snow package

# TeeUniverse 0.1.0 #

## Binaries ##

* [Linux 64-bit binaries](https://github.com/teeuniverse/teeuniverse/releases/download/v0.1.0/teeuniverse-0.1.0-linux_x86_64.tar.gz)
* [Source code (zip)](https://github.com/teeuniverse/teeuniverse/archive/v0.1.0.zip)
* [Source code (tar.gz)](https://github.com/teeuniverse/teeuniverse/archive/v0.1.0.tar.gz)

## Change Log ##

### Note ### 

- The first version of TeeUniverse.


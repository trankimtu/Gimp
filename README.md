# Gimp

## Installation:
  [Download Gimp](https://www.gimp.org/downloads/)

  Layer effect 
## Introduction
  Main menu:<br>
  Toolbox: Contains all tools<br>
  Tool options: Contains settings for the tool we have selected<br>
  Canvas: Display image or composition<br>
  Layer, Channels, Paths, Undo: Display items mentioned in its name<br>
  Brush, Patterns, Fonts, Document History<br>

  Toolbox:<br>
    Selection tools: Allow select the area of the image using various methods. Then make changes in isolated items that are in the specified selection area.<br>
    Paint tools: Free draw or paint<br>
    Transform tools: Transform an active layer, selection area, or path<br>
    Other tools<br>

  Search tools: /

## Setup Interface
### Use Single window mode, uncheck Hide Docks
```
  Windows -> Single Window mode
  Windows -> Hide Docks
```
### Default Image
- Set Default image size, resolution, 
```
  Edit -> References -> Default Image
  Precision: low for slow PC
```
### Dark mode:
```
  Edit -> References -> Interface -> Theme
```
### Modify Toolbox:
```
  Edit -> References -> Interface -> Toolbox
```
### Tab
```
  Relocation tab: move it to the edge to make another column
  Select tab, click to top right corner
  - Tab Style
  - Lock tab to Dock
```
### Save Windows location
```
  Set location tool tab
  Edit -> References -> Interface -> Window Management -> Save Window Positions Now
  Top right: Tool Options, Device Status, Brushes, Patterns, Fonts
  Bottom right: Layers, Channels, Paths, Document History, Undo History, Images
  
```
### Save Default Option
```
  Move: Move the active layer
  Color Picker Tool (eye drop icon): Sample average, Radius = 3(default)
  Healing Tool (band aid icon): Alignment = Aligned
  Crop Tool: Guide = Rule of thirds
  Clone tool: Active Sample merged, Alignment = Aligned
  Edit -> References -> Input Devices -> Save Input Device Setting Now
```
### System Resources
```
  Edit -> References -> System Resources
  Base on how much Ram 
  - Minimal number of undo levels: 500 (Start with 100 and increasing up if needed)
  - Maximum undo memory: 8 Gb
  - Sze of thumbnails: Large(256x256) 
```
### Color Management
```
  Edit -> References -> Color Management -> Policies -> File Open behavior:
  - Ask what to do:
  - Keep embedded file
  - Convert to preferred RGB color profile: If we output to a professional lab, they may have a specific RGB profile that they prefer the images to be in before submtting the order. They will give the file to import to Preferred Profiles -> RGB profile.
  - Extra info: If we're going to send a document out fo a Four Color press because we're printing up a prochure or flyers or business card or whatever that may be then we may want to get the CMYK color profile which is the four color of a print press so we have C = Cyan, M = Magenta, Y = Yellow, K = back. We're going to also want to work in this profile if we're going to create our documents in Gimps and then output it to that CMYK press.
```
### Image Import & Export
```
  Edit -> References -> Image Import & Export
  Export Exif, XMP, IPTC metadata: we may take this off if we dont want to share location or any information in metadata of the picture when post the picture on facebook or any social media site

```
### Toolbox
```
  Edit -> References -> Interface -> Toolbox
  May want to uncheck"Show GIMP logo (drag-and-drop target)"
  Check "Show active brush, pattern & gradient
  May want to add "Levels" and "Curves" tools to toolbox
```
<!-- ============================================== -->

## Using
### Change image Precision
```
  Image -> Precision -> 32 bit floating point
  Gamma: Linear light for the highest setting 
```
### Scroll
```
  Up / Down
  Shift + Scroll = Left / Right
```
### Zoom
```
  + / -
  Ctrl + Scroll
```
### Pan
```
  Spacebar
  Middle button (Scroll button)
```
### Layer display
```
  Only show 1 layer: Shift + eye
```
### Selection
```
  Select none: Ctrl + Shift + a
```
### Move
```
  Shortcut: m
  Option: Move the active layer
```


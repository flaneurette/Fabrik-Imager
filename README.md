# Fabrik Imager

<img src="screen.png" />

A minimalist graphic photo editor to edit and create images. Not the same as Gimp, Photoshop, Photopea, Canva or Paint, but rather unique as it has limited, but creative! functions.

2000+ line code, makes it very portable. All images are exported with quality control, and are streamed as a blob to download. No server-side technology needed.

Has the most used functions, for simplicity:

Image support:

PNG, JPEG, GIF, AVIF. (except for Firefox, which only support PNG blobs)

Menu:

- Open/save images files. (also: save a selection)
- Magic wand
- Brushes, styles: pencil, round, square, spray, rand. wih dedicated color picker.
- Drag/Pointer
- Resize a layer
- Rectangle
- Circles
- Flood Fill/Bucket
- Color picker
- Zoom +/-
- Text & System Fonts.
- Eraser
- Rotate layers (left/right mouse button to rotate direction, snaps into place at certain angles)
- Canvas resizer
- Various standard effects/filters: blur, saturate, neon, hue, contrast, noise, etc.
- Custom Fabrik filters (folded paper, fine grain, rice paper, confetti, etc.)

Right menu:

Layers
- Add layer
- Delete layer
- Merge layers
- Dupe layer
- Move layer

Most popular shortcuts: `ctrl+e` to merge layers, `ctrl+c` to copy layer, `ctrl+v` to paste, `ctrl+x` to cut a layer.

TIP: Use `middle mouse button` to drag layers, or items around.

TIP: Many filters require good hardware. i.e. a fast CPU and GPU. At best, some filters take 3-10 seconds to be applied.

TIP: Firefox browser does not support (yet) anything else but PNG export when using blob.
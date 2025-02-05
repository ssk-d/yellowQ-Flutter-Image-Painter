# 0.3.2

- Bumped up dependencies.
- Generated dartdoc api documentation.

# 0.3.1

- Fix static analysis

# 0.3.0

**Breaking Changes:** 
- `Controller` is no longer required to pass as the editor will handle it manually. 
- No need to configure controls options. Package provides control bar with all the needed features like change mode, color, undo, clear etc. 
- Text mode is available now. After adding text, it can be moved freely around until next operation. 
- The `PaintMode` enums are now lowercases following dart conventions.


# 0.2.0

- Fixed issue with image parsing failing when used with file. 
- Added exceptions to the image conversion failures.
- Fixed lint issues.

# 0.1.9

- Smoother look for signature mode.
- Local InteractiveViewer for future flutter version issues. 

# 0.1.8

- Added dynamic strokeMultiplier to compensate strokewidth for high resolution image.
- Pan or moving around image is available to use when mode is `PaintMode.none`. 
- Performance improvements and lint fixes. 
- Improved example. 

# 0.1.6

- ByteArray on memory constructor now returns itself without conversion back if no action is performed on it.
- Code refactors.

# 0.1.5

- Breaking Change: Controller is immutable and can only be overridden with copyWith Constructor.
- Added PaintStyle in constructor.
- Code refactor.

# 0.1.4

- Fixed ImagePainter.memory constructor taking ui.Image while it should be taking Uint8List. 

# 0.1.3

- Added signature field. 
- Fixed scaling issues.
- Added example for signature field. 

# 0.1.1

- Added documentation to the class and functions.
- Improved docs and readMe.

# 0.1.0

Initial version of image_painter library.
 - Includes 7 modes of paint styles i.e. Line, Box/Rectangle, Circle, FreeStyle or Signature, Arrow, Dash/Dotted Lines and Text 
 - Includes controls for color and StrokeWidth.
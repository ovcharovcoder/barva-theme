# Changelog

All notable changes to the Barva Theme VS Code extension will be documented in this file.
The format is based on Keep a Changelog, and this project adheres to Semantic Versioning.
<br>

## [1.0.9 - 1.1.0] - 2025-10-06  
**Fixed**
- Correction of the error displaying the author's avatar and other minor errors.

## [1.0.8] - 2025-10-05  
### Added
- New **Light Themes**: Barva Calm Light, Barva Cloud Light, Barva Dawn Light, Barva Mist Light  
- New **Dark Themes**: Barva Calm Dark, Barva Cloud Dark, Barva Dawn Dark, Barva Mist Dark  
- Semantic token highlighting improvements for new themes 
- Updated installation instructions to include all new theme variants  

## [1.0.7] - 2025-10-04  
### Added
- **Video preview:** Added a YouTube video demonstrating how the Barva Theme looks in VS Code.  

### Changed
- **README improvements:** Rewritten and refined description for better clarity and presentation.    

## [1.0.6] - 2025-10-02  
### Fixed 
- **Reduced eye strain and improved text sharpness:**  
  Adjusted base foreground color from #C7D0C7 to #E0E5E0 for light theme.  

## [1.0.5] - 2025-10-01  
### Fixed  
- **Improved documentation comment readability:**  
  Replaced `"italic bold"` styling for `comment.block.documentation` with standard `"italic"` to enhance clarity when rendering complex character sets (CJK: Chinese, Japanese, Korean).  
  This change prevents glyph blurring and improves stroke definition for multilingual codebases.

- **Reduced eye strain and improved text sharpness:**  
  Adjusted base foreground color from `#E0E5E0` to `#C7D0C7` (≈90% brightness) for dark theme.  
  This provides a more comfortable visual contrast, reduces glare during extended sessions, and maintains hue consistency with the theme’s original palette.

## [1.0.4] - 2025-06-18

**Fixed**
- Softer active line highlight: Changed editor.lineHighlightBackground to #3A6F9F1A (light blue with 5% opacity) for a less distracting and more harmonious appearance in the code editor.

## [1.0.3] - 2025-06-18

**Added**
- Added titleBar, badge, editorSuggestWidget, editorCodeLens, and editorHoverWidget colors for complete VS Code UI support.
- Introduced contrastActiveBorder (#7A9AD4) for active element highlighting.
- Added all terminal.ansi* and terminal.ansiBright* colors (e.g., ansiBrightCyan: #2AA198, ansiMagenta: #B16286) for enhanced terminal compatibility.
- Added keyword.operator, string.template, and comment.block.documentation in tokenColors for better language support (e.g., JavaScript, Python).
- Expanded semanticTokenColors with method, property, and namespace for improved semantic highlighting.
- Included author and version fields in theme JSON for better documentation.

**Fixed**
- Corrected invalid keyword.operator structure in tokenColors (removed erroneous robot key).
- Standardized gitDecoration.conflictingResourceForeground (#C586C0) for Git conflict visibility.
- Enhanced editorLineNumber.foreground from #6B7280 to #7F8C8D for improved readability (~4.6:1 contrast ratio on #252A27 background).
- Adjusted editorError.foreground (#E55B5B → #FF4D4D) and editorWarning.foreground (#FFD107 → #FFCA28) for softer, high-contrast visuals.
- Increased opacity for editor.lineHighlightBackground (#7A9AD422 → #7A9AD455), editor.selectionBackground (#7A9AD455 → #7A9AD466), and scrollbarSlider for better visibility.
- Changed list.focusBackground to #4A5653 to distinguish from list.activeSelectionBackground (#3A423F).
- Improved terminalCursor.foreground to #E0E5E0 for higher contrast on #2D3532 terminal background.
- Aligned accent colors: #7A9AD4 (dark) matches #3A6F9F (light).
- Harmonized error colors: #FF4D4D (dark) matches #B71C1C (light).
- Synced warning colors: #FFCA28 (dark) matches #A17646 (light).
- Matched string colors: #7BC07B (dark) matches #5B8C5A (light).


## [1.0.2] - 2025-06-14

**Added**
- Linen-like background for the light theme (#FAF5ED) — inspired by natural flax fabric, reduces eye strain.
- Improved contrast in menus and sidebars:
  - Highlighted menu text changed from white to dark gray (#2A2F2C).
  - Same adjustments for active files in the Side Bar.

- Color synchronization between light/dark themes for consistency:
  - Blue: #3A6F9F (light) / #7A9AD4 (dark).
  - Red: #C53030 (light) / #E55B5B (dark).

**Fixed**
Enhanced readability:
- Error/warning colors are now less aggressive (e.g., #A61C3C → #C53030).
- Comments are lighter (#A3A9A6 with italics) for better contrast.


## [1.0.1] - 2025-06-13

**Added**
- The dark theme has had its color scheme improved to make it more pleasing to the eyes.


## [1.0.0] - 2025-06-10

**Added** 
- Initial release of Barva Theme with light and dark variants inspired by Ukrainian vyshyvanka embroidery.
- Support for multiple programming languages (JavaScript, CSS, Python, PHP, C++, Ruby, Java, C#).
- Customizable syntax highlighting with vibrant colors.
- Semantic highlighting enabled for better code readability.

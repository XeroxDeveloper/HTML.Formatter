# Changelog - HTML Formatter

## Version 1.3.0

### New Features
- Added support for headers (h1-h6) with colored emoji prefixes
- Added text styling tags: small, big, center, right
- Added scientific tags: sup, sub
- Added special elements: kbd, var, samp, mark
- Added semantic tags: strong, em, del, ins
- Added blockquote and horizontal line support

### Technical Improvements
- Enhanced recursive tag processing
- Added maximum iteration limit to prevent infinite loops
- Improved Unicode character mapping
- Better error handling for malformed HTML

### Tag Examples
- Headers: `<h1>Header 1</>`, `<h2>Header 2</>`, etc.
- Text styles: `<small>small text</>`, `<big>big text</>`
- Alignment: `<center>centered</>`, `<right>right aligned</>`
- Scientific: `<sup>superscript</>`, `<sub>subscript</>`
- Special: `<kbd>keyboard</>`, `<var>variable</>`

### Bug Fixes
- Fixed nested tag processing issues
- Improved link attribute parsing
- Better handling of special characters

**Creator**: @username_taked  
**Requirements**: exteraGram 11.9.0+

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Visit_Site-d4351c?style=for-the-badge)](https://mikky-mlh.github.io/OFE/)

# Editor - ONE HTML FILE CHALLENGE 🎯

A powerful, feature-rich rich text editor packed into a single HTML file. Create, edit, and export documents in multiple formats—all from one interface with live preview.

## 🏆 Challenge Compliance

This project was built as a **ONE HTML FILE CHALLENGE** submission:
- ✅ All code in 1 single HTML file (~47KB)
- ✅ Under 1MB file size limit
- ✅ No external file imports
- ✅ No network requests
- ✅ Pure vanilla JavaScript, CSS, and HTML

## ✨ Features

### 📝 Rich Text Editing
- **Text Formatting**: Bold, Italic, Underline, Strikethrough
- **Advanced Formatting**: Subscript, Superscript
- **Headings**: H1 through H6 support
- **Paragraph Styles**: Normal text, code blocks, blockquotes
- **Font Customization**: Multiple font families and sizes
- **Color Controls**: Text color and highlight/background color with visual color picker

### 📐 Layout & Alignment
- **Text Alignment**: Left, Center, Right, Justify
- **Lists**: Bulleted (unordered) and numbered (ordered) lists
- **Indentation**: Indent and outdent controls
- **Horizontal Rules**: Visual section dividers

### 🖼️ Media & Content
- **Images**: Insert from URL or upload from device (converted to base64)
- **Videos**: Embed YouTube and Vimeo videos with auto-detection
- **Tables**: Dynamic table creation with customizable rows, columns, and optional headers
- **Links**: Hyperlinks with custom text and target options (new tab/same tab)

### 👁️ View Modes
- **Split View**: Edit and preview side-by-side (default)
- **Editor Only**: Focus on writing without distractions
- **Preview Only**: See your formatted content
- **Live Sync**: Real-time preview updates as you type

### 💾 Export Formats
Export your content to multiple file formats:
- **HTML** (.html) - Standalone web page with embedded styles
- **PDF** (.pdf) - Print-ready document via browser print dialog
- **Markdown** (.md) - Full HTML-to-Markdown conversion
- **Word** (.docx) - Microsoft Word compatible (Office Open XML format)
- **Plain Text** (.txt) - Clean text without formatting

### 🎨 User Interface
- **Modern Design**: Clean, professional interface with custom color scheme
- **Responsive Layout**: Works on desktop and mobile devices
- **Intuitive Toolbar**: All formatting options easily accessible
- **Modal Dialogs**: User-friendly popups for complex insertions
- **Toast Notifications**: Helpful feedback messages
- **Color Picker**: Visual color selection with 40 preset colors

### 💪 Advanced Features
- **Auto-Save**: Content automatically saved to browser localStorage
- **Word & Character Count**: Real-time statistics in status bar
- **Keyboard Shortcuts**: 
  - `Ctrl+B` - Bold
  - `Ctrl+I` - Italic
  - `Ctrl+U` - Underline
  - `Ctrl+Z` - Undo
  - `Ctrl+Y` - Redo
  - `Ctrl+S` - Save to localStorage
  - `Esc` - Close color pickers
- **Clear Formatting**: Remove all formatting from selected text
- **Selection Memory**: Maintains cursor position when using modals

### 🔧 Technical Highlights
- **Pure JavaScript**: No external libraries or dependencies
- **Custom DOCX Generator**: Built-in Office Open XML writer with ZIP compression
- **HTML to Markdown Converter**: Complete conversion engine
- **Base64 Image Encoding**: Upload images without external hosting
- **ContentEditable API**: Native browser editing capabilities
- **LocalStorage Integration**: Persistent content across sessions

## 🚀 Usage

1. Open `index.html` in any modern web browser
2. Start typing in the editor pane
3. Use the toolbar to format your content
4. Watch the live preview update in real-time
5. Export to your desired format when finished

## 🎯 Use Cases

- **Quick Note Taking**: Fast, distraction-free writing
- **Document Creation**: Professional documents with formatting
- **Blog Post Drafting**: Write in rich text, export to Markdown
- **Content Conversion**: Convert between HTML, Markdown, and Word formats
- **Offline Editing**: No internet required, works completely offline
- **Educational Tool**: Learn about contentEditable and document formats

## 🌐 Browser Compatibility

Works in all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

## 📦 File Structure

Everything is contained in `index.html`:
- **HTML**: Document structure and UI elements
- **CSS**: Complete styling with custom properties and animations
- **JavaScript**: All functionality including export engines

## 🎨 Customization

The editor uses CSS custom properties for easy theming:
```css
--ink: #1a1a1a;        /* Text color */
--paper: #fdfcf8;      /* Background */
--accent: #d4351c;     /* Primary accent */
--border: #e8e6df;     /* Border color */
--toolbar: #f5f3ed;    /* Toolbar background */
```

## 🔒 Privacy

- **No tracking**: Zero analytics or external requests
- **Local storage only**: Your content never leaves your device
- **No server**: Completely client-side application
- **No cookies**: No tracking mechanisms

## 💡 Technical Implementation

### Export Engines

**HTML Export**: Wraps content in a complete HTML5 document with embedded styles

**PDF Export**: Uses browser's native print functionality with custom print styles

**Markdown Export**: Custom HTML-to-Markdown parser supporting:
- Headings, paragraphs, line breaks
- Bold, italic, strikethrough, code
- Links, images, horizontal rules
- Ordered and unordered lists
- Tables with proper formatting
- Blockquotes with nested content

**DOCX Export**: Pure JavaScript implementation:
- Custom ZIP builder (STORE method, no compression)
- Office Open XML document generation
- Proper Word document structure with relationships
- Styled paragraphs, headings, and tables
- CRC32 checksum calculation

**TXT Export**: Strips all HTML tags, preserving plain text content

## 🏅 Challenge Achievement

This project demonstrates:
- Advanced JavaScript programming
- DOM manipulation and contentEditable API
- File format understanding (ZIP, DOCX, Markdown)
- Binary data handling (Uint8Array, DataView)
- CSS animations and modern layout techniques
- User experience design
- Code optimization for size constraints

---

**Built with ❤️ as a ONE HTML FILE CHALLENGE**

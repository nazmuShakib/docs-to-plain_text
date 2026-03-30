# 📄 Docs → Plain Text Converter

A free, browser-based tool that converts formatted documents to plain text while preserving structure such as numbered lists, nested lists, headings, and paragraphs.

---

## ✅ What It Supports

### 📁 Upload Mode (.docx files)
| Feature                                     | Status                                                            |
| ------------------------------------------- | ----------------------------------------------------------------- |
| Numbered lists (`1.` `2.` `3.`)             | ✅ Supported                                                       |
| Lettered sub-lists (`a.` `b.` `c.`)         | ✅ Supported                                                       |
| Roman numeral sub-lists (`i.` `ii.` `iii.`) | ✅ Supported                                                       |
| Nested lists (multiple levels deep)         | ✅ Supported                                                       |
| Bullet point lists (`•`)                    | ✅ Supported                                                       |
| Blank lines / empty paragraphs              | ✅ Preserved                                                       |
| Regular paragraphs                          | ✅ Supported                                                       |
| Headings (H1–H6)                            | ✅ Supported                                                       |
| Tables                                      | ✅ Supported (plain text layout)                                   |
| Bold / Italic / Underline text              | ✅ Preserved as markdown (`**bold**`, `_italic_`, `__underline__`) |
| `.docx` drag and drop                       | ✅ Supported                                                       |
| `.docx` click to upload                     | ✅ Supported                                                       |

### 📋 Paste Mode (Google Docs)
| Feature                        | Status                          |
| ------------------------------ | ------------------------------- |
| Numbered lists                 | ✅ Supported                     |
| Nested lists                   | ✅ Supported                     |
| Bullet point lists             | ✅ Supported                     |
| Blank lines / empty paragraphs | ✅ Preserved                     |
| Regular paragraphs             | ✅ Supported                     |
| Headings (H1–H6)               | ✅ Supported                     |
| Tables                         | ✅ Supported (plain text layout) |
| Bold / Italic / Underline text | ✅ Preserved as markdown         |
| Paste with Ctrl+V / Cmd+V      | ✅ Supported                     |

### 🛠️ Editor Features
| Feature                         | Status      |
| ------------------------------- | ----------- |
| Download as `.txt` file         | ✅ Supported |
| Copy all text to clipboard      | ✅ Supported |
| Clear editor                    | ✅ Supported |
| Editable output before download | ✅ Supported |
| Resize editor window            | ✅ Supported |

---

## ⚠️ Known Limitations

| Limitation                     | Notes                                      |
| ------------------------------ | ------------------------------------------ |
| `.doc` files (old Word format) | ❌ Not supported — convert to `.docx` first |
| `.pdf` files                   | ❌ Not supported                            |
| Google Sheets / Excel          | ❌ Not supported                            |
| Images inside documents        | ❌ Ignored / not extracted                  |
| Complex table formatting       | ⚠️ Basic plain text layout only             |
| Password-protected files       | ❌ Not supported                            |
| Google Docs direct URL         | ❌ Must paste content manually              |

---

## 🔒 Privacy
- **No data is sent to any server**
- All processing happens entirely in your browser
- Your files and text never leave your device

---

## 🌐 Browser Compatibility
| Browser         | Status                                       |
| --------------- | -------------------------------------------- |
| Chrome          | ✅ Fully supported                            |
| Edge            | ✅ Fully supported                            |
| Firefox         | ✅ Fully supported                            |
| Safari          | ✅ Fully supported                            |
| Mobile browsers | ✅ Supported (upload mode may vary by device) |

---

## 🚀 How to Use

### Option A — Paste from Google Docs
1. Open your document in Google Docs
2. Select all text (`Ctrl+A` / `Cmd+A`)
3. Copy (`Ctrl+C` / `Cmd+C`)
4. Click **📋 Paste Mode** tab on the tool
5. Paste into the editor (`Ctrl+V` / `Cmd+V`)
6. Formatting is automatically converted to plain text

### Option B — Upload a .docx File
1. Click **📁 Upload Mode** tab
2. Drag and drop your `.docx` file or click to browse
3. File is automatically converted
4. Edit if needed, then download or copy

---

## 🛠️ Built With
- Vanilla HTML / CSS / JavaScript (no framework)
- [Mammoth.js](https://github.com/mwilliamson/mammoth.js) — .docx to HTML conversion
- [JSZip](https://stuk.github.io/jszip/) — .docx XML extraction for accurate list formatting
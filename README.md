# text-compare

![text-compare](https://img.shields.io/badge/version-1.1.4-blue.svg) ![License](https://img.shields.io/badge/license-MIT-green.svg)

A minimal, client-side web app for visually comparing two blocks of text using CodeMirror and Mergely.

## 🔍 Overview

**text-compare** provides a lightweight browser-based diff/merge interface that highlights differences between two text inputs. It uses CodeMirror for editable text areas and Mergely for visual diff rendering.
![screenshot](https://upload.hackettlai.com/default/2026/screenshot-1768203319316.png)

## 🔗 Libraries

- [Mergely](https://github.com/wickedest/Mergely) — Visual diff/merge engine used for side-by-side comparison.
- [CodeMirror 5](https://github.com/codemirror/codemirror5) — Browser-based code editor used for editable panels.

## ✅ Features

- Side-by-side text comparison
- Syntax highlighting (via CodeMirror)
- Uses Mergely for diff/merge visualization
- No backend — runs entirely in the browser

## Demo 🎬

[Live Demo](https://text-compare.hackettlai.com)

## 🚀 Quick start

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/text-compare.git
   cd text-compare
   ```

2. Serve the folder and open in your browser (recommended):

   ```bash
   # Python 3
   python3 -m http.server 8000
   # then open http://localhost:8000 in your browser
   ```

   Opening `index.html` directly from the filesystem may work in some browsers, but serving via HTTP avoids cross-origin issues.

## 🛠️ Development

- Main entry: `index.html`
- Styling: `sytle.css` (note: file name is `sytle.css` in the repo)
- Vendor CSS: `css/bootstrap.min.css`, `css/codemirror.min.css`, `css/mergely.css`
- Vendor JS: `js/jquery.min.js`, `js/bootstrap.bundle.min.js`, `js/codemirror.min.js`, `js/mergely.js` and small helper scripts in `js/`

To modify behavior, edit `index.html` and the scripts in `js/` and then reload the page.

## 🤝 Contributing

Contributions are welcome. Please open an issue or a pull request with a clear description of your change.

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

⭐ If you find this tool useful, please consider giving it a star on GitHub!
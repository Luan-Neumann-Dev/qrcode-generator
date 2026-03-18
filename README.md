# QR Code Generator
 
> Instantly generate a QR code from any URL or text — directly in the browser, no libraries required.
 
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

![Project Preview](https://github.com/user-attachments/assets/620f3ca2-f6d5-43aa-b07a-c7c2a787ab69)
![Project Preview](https://github.com/user-attachments/assets/f878399c-55d7-46c5-aa45-60a698fef6d3)
## 🎯 About
 
QR Code Generator is a minimal browser tool that converts any URL or text into a QR code image on demand. It consumes the [goQR.me public API](https://goqr.me/api/) to generate the image, and uses a CSS class toggle to animate the card expanding and revealing the result — no page reload, no libraries.
 
## ✨ Features
 
- 🔗 **URL & Text Support** - Generate QR codes from any input string
- ⌨️ **Keyboard Friendly** - Trigger generation by pressing Enter
- 🎞️ **Animated Reveal** - Card smoothly expands to display the QR code on load
- 🔄 **Auto Reset** - Clears and collapses the card when the input is emptied
 
## 🛠️ Built With
 
- **HTML5** - Minimal structure with an input, button, and image container
- **CSS3** - CSS transitions and `.active` class toggle for the expand/collapse animation
- **JavaScript** - Event handling, dynamic `img.src` API call, and `load` event for timing the reveal
- **goQR.me API** - Free public API that returns a QR code image from a query string parameter
 
## 🚀 Getting Started
 
### Prerequisites
 
- A modern web browser (Chrome, Firefox, Safari, Edge)
- An internet connection (required to fetch the QR code from the API)
 
### Installation
 
```bash
# Clone the repository
git clone https://github.com/Luan-Neumann-Dev/qrcode-generator.git
 
# Navigate to project directory
cd qrcode-generator
 
# Open in browser
open index.html
```
 
## 📁 Project Structure
 
```
qrcode-generator/
├── index.html          # App markup — input form and QR code display area
├── css/
│   └── style.css       # Card layout, transition animations, and active state
├── js/
│   └── script.js       # Input events, API call via img.src, and UI state updates
└── img/
    └── qrcode.png      # Placeholder image shown before generation
```
 
## 🎓 What I Learned
 
- Consuming a public REST API without `fetch` — using a dynamic `img.src` URL with query parameters
- Timing UI updates with the `img load` event to ensure the image is ready before revealing it
- Toggling CSS classes from JavaScript to drive smooth layout transitions
- Handling multiple input events (`click`, `keydown`, `keyup`) for a better user experience
 
## 📝 Notes
 
- This is a **frontend-only** project — QR code generation is handled entirely by the external API
- Requires an internet connection to generate codes
- QR code images can be saved directly by right-clicking the generated image
 
## 📄 License
 
This project is open source and available under the MIT License;
 
## 👤 Author
 
**Luan Neumann**
 
- LinkedIn: [Luan-Neumann-Dev](https://www.linkedin.com/in/luan-henrique-neumann-dev/)
- GitHub: [@luan-neumann-dev](https://github.com/Luan-Neumann-Dev)
 
---
 
⭐ If you found this project helpful, consider giving it a star!

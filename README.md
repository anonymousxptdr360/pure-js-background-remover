# Pure JS Background Remover 🎨

A lightweight, client-side web tool designed to remove solid or uniform backgrounds from images. This project is built with pure JavaScript and HTML5 Canvas, making it fast, private, and easy to use.

---

## 🚀 Live Demo
You can use the software directly in your browser without any installation:
👉 **[Try it here](https://stopbordo.odoo.com/suppresseur-de-fond)**

---

## 📖 Description
This tool is specifically designed for **logos, icons, and graphics with flat backgrounds**. Unlike AI-powered background removers, this script uses a color-distance algorithm. It samples the top-left pixel of your image and removes all similar colors based on your chosen tolerance level.

### ⚠️ Important Limitations
* **No AI involved:** This tool does not "recognize" subjects (people, animals, objects).
* **Ideal for:** Logos on white/black backgrounds, simple icons, and flat-color graphics.
* **Not for:** Complex photography, landscapes, or portraits with busy backgrounds.

## ✨ Features
* **Privacy First:** No images are uploaded to a server. All processing happens locally in your browser.
* **Real-time Tolerance:** Adjust the slider to handle anti-aliasing or slight color variations.
* **High Quality:** Supports PNG export with full transparency.
* **Responsive UI:** Built with Tailwind CSS for a clean experience on mobile and desktop.

---

## 📥 Access & Downloads

* **Latest Release:** Download the ready-to-use HTML file here:  
    [Download 1.0](https://github.com/anonymousxptdr360/pure-js-background-remover/releases)

* **Source Code:** View the raw code directly here:  
    [1.0-pure-js-background-remover.html](https://github.com/anonymousxptdr360/pure-js-background-remover/blob/main/1.0-pure-js-background-remover.html)

---

## 🛠️ How it Works
1.  **Upload** your image (PNG, JPG, or WEBP).
2.  The script identifies the **top-left pixel** as the background color.
3.  Adjust the **Tolerance** slider if bits of the background remain.
4.  Click **"Remove Background"** and download your transparent PNG.

## 📝 License
This project is open-source. Feel free to use, modify, and share!

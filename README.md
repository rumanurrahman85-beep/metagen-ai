# MetaGen AI — Stock Metadata Generator

AI-powered metadata generator for stock contributors. Upload any creative file (JPG, PNG, EPS, PSD, AI, SVG, SPZ, TIFF, PDF...) and Gemini AI generates SEO-optimized title, description, and keywords — ready for Shutterstock, Adobe Stock, Getty Images, Freepik, Dreamstime, and more.

## 🚀 Deploy to GitHub Pages (5 minutes)

1. **Create a new GitHub repository** (e.g. `metagen-ai`)
2. **Upload `index.html`** to the root of the repo
3. Go to **Settings → Pages**
4. Under *Source*, select **Deploy from a branch → main → / (root)**
5. Click **Save**
6. Your site will be live at: `https://YOUR-USERNAME.github.io/metagen-ai/`

That's it. No backend, no server, no cost.

## 🔑 Gemini API Key

- Get a free key at: https://aistudio.google.com/app/apikey
- Paste it into the app each session — it is **never stored** anywhere
- The key only leaves your browser to call Google's Gemini API directly

## 📁 What gets downloaded

For each file you process, you get:

| Output | Format | Use |
|--------|--------|-----|
| `filename.xmp` | XMP Sidecar | Drag into Adobe Bridge, Lightroom, or upload alongside your file on stock sites |
| `filename_metadata.txt` | Plain text | Copy/paste metadata directly into stock platform upload forms |

Batch download packs everything into a single `.zip` file.

## ✅ Supported File Types

JPG · PNG · WEBP · GIF · TIFF · BMP · SVG · EPS · AI · PSD · SPZ · PDF · ZIP

> **Note:** For image formats (JPG, PNG, WEBP, SVG), Gemini *visually analyzes* the image to generate accurate metadata. For binary formats (EPS, PSD, AI, SPZ), it uses the filename and your selected settings to generate metadata — you can edit the result before downloading.

## ⚖️ IP / Copyright Notice

- Only upload files you own or have rights to
- Do not generate metadata for copyrighted characters, logos, or trademarked brands
- The app includes built-in prompts that instruct Gemini to keep all metadata IP-safe and commercially licensable
- Always verify AI-generated content before submitting to stock platforms

## 🛠️ Customization

Everything is in a single `index.html` file. You can:
- Change the color scheme in the `:root` CSS variables
- Add more platforms to the dropdown
- Adjust keyword count defaults
- Translate the UI to your language

---

Built with ❤️ by [Noavecta](https://noavecta.webdesignerm.com) · Powered by Google Gemini

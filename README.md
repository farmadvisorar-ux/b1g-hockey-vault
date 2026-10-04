# B1G Hockey Vault Embed Site

A modern, responsive web application that embeds the [B1G Hockey Vault](https://b1g-hockey-vault-lmsaumqmy-wordwide-top-10.vercel.app/).

## Features
- **Accurate Embed**: Incorporates the exact iframe specification (`width="420" height="600"`, full permissions, responsive adaptation).
- **Modern UI**: Sleek sports/ice-hockey inspired dark theme, ambient mesh grid, subtle neon highlights, and window chrome.
- **Controls**:
  - **Reload**: Refresh the embedded iframe without reloading the parent website.
  - **Expand / Reset View**: Switch smoothly between the original 420x600 dimensions and an expanded theater mode.
  - **Open Direct**: Quick link to launch the original URL directly in a new tab.
- **Loading State**: Smooth animated spinner while the iframe content connects and initializes.

## How to Run

### Option 1: Direct in Browser
Double-click `index.html` to open it immediately in any modern web browser (Edge, Chrome, Firefox, etc.).

### Option 2: Local HTTP Server (Python)
In PowerShell or terminal:
```powershell
cd C:\Users\Admin\.gemini\antigravity\scratch\hockey-vault-embed
python -m http.server 8080
```
Then visit [http://localhost:8080](http://localhost:8080) in your browser.

### Option 3: Deploy to Vercel / GitHub Pages / Netlify
This is a standard static HTML5 project. You can drop `index.html` into any static host (e.g., GitHub Pages, Cloudflare Pages, Vercel, Netlify) with zero configuration needed.

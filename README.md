# Shortcode Dial Demo

A minimal static page that demonstrates a "tap to auto-dial" shortcode link on mobile devices. Tapping the button triggers the IMEI shortcode (`*#06#`) via a `tel:` link.

**Live Demo:** https://rogamorris.github.io/shortcode-dial-demo/

## Local Testing

Open `index.html` directly in a browser. On mobile, tapping the button opens the dialer. On desktop, nothing happens (as expected).

## GitHub Pages Setup

1. Push this repository to GitHub
2. Go to your repository on GitHub
3. Click **Settings** (top menu)
4. Click **Pages** (left sidebar, under "Code and automation")
5. Under **Source**, select:
   - **Branch:** `main` (or `master`)
   - **Folder:** `/ (root)`
6. Click **Save**
7. Wait 1-2 minutes for deployment
8. Your site will be live at: `https://<username>.github.io/<repo-name>/`

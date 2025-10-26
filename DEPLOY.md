# Deploy to Vercel

## Steps:

1. **Install Vercel CLI** (optional):
   ```bash
   npm i -g vercel
   ```

2. **Deploy via Web**:
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Upload this folder or connect GitHub repo
   - **Framework Preset**: Select "Other" or "Static Site"
   - Deploy automatically

3. **Deploy via CLI**:
   ```bash
   vercel
   ```

4. **Your app will be live at**:
   - `https://your-project-name.vercel.app`

5. **Install on Android**:
   - Open the Vercel URL in Chrome
   - Tap menu → "Add to Home screen"
   - App installs as PWA

## Files included:
- terminal.html (main app)
- manifest.json (PWA config)
- sw.js (service worker)
- icon-192.png (app icon)
- vercel.json (deployment config)
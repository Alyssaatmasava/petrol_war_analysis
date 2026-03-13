# Dashboard Screenshots

To add a screenshot of your dashboard to the README:

1. **Launch the dashboard locally:**
   ```bash
   cd dashboard
   python -m http.server 8000
   ```

2. **Open in browser:** http://localhost:8000/petrol-war-dashboard.html

3. **Take a screenshot:**
   - On macOS: Cmd+Shift+4, then drag to select the dashboard area
   - On Windows: Win+Shift+S
   - On Linux: Use your screenshot tool (e.g., Flameshot, Shutter)

4. **Save as:** `dashboard-preview.png` in the `assets/` folder

5. **Recommended:** Capture the main dashboard view showing the navigation tabs and key metrics

## Alternative: GIF Animation

For a more dynamic preview, create a GIF showing tab navigation:

1. Use a screen recording tool (e.g., OBS Studio, ScreenToGif, or macOS built-in)
2. Record yourself clicking through the different tabs
3. Export as GIF and save as `dashboard-demo.gif`
4. Update the README image link accordingly

## GitHub Pages Setup

To enable live demo:

1. Go to your GitHub repository
2. Settings → Pages
3. Source: "Deploy from a branch"
4. Branch: main, folder: / (root)
5. The dashboard will be available at: https://yourusername.github.io/repository-name/

Note: You may need to update relative paths in the HTML if data files are referenced.
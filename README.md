# SpiralSense Website

This is the standalone, working SpiralSense frontend.

## Publish on GitHub Pages

1. Put `index.html` and `config.js` in the folder served by GitHub Pages.
2. Put the separate `spiralsense-extension.zip` file in the **same published folder**.
3. Keep `window.SPIRALSENSE_EXTENSION_URL` in `config.js` as `./spiralsense-extension.zip`.
4. Enable GitHub Pages for the branch/folder containing those files.

The **Add extension** buttons then download the actual extension ZIP.

## Dashboard

The dashboard has working local analytics, activity history, charts, reports, focus-session counters, and privacy information. When the SpiralSense extension is installed and the site is opened in Chrome, the extension can sync its locally stored analytics into the dashboard.

No page content is read by the detector; it uses scroll movement/timing signals.

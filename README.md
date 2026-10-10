# SafeSpace AI – 3D scroll website

Single-file project. No install, no build step.

## Run in VS Code
1. Unzip and open the `safespace-ai` folder in VS Code (File > Open Folder).
2. Install the "Live Server" extension (Ritwick Dey).
3. Right-click `index.html` > "Open with Live Server".

Or just double-click `index.html` to open it in any browser.

## Edit
- All text, colours and styles are inside `index.html`.
- Colours: the `:root{...}` block at the top of the `<style>` tag.
- Replace placeholders: [Name], [Names], [Team name], [Demo link].

## Make it an Android app (APK) later
- Easiest: host the folder (Netlify / GitHub Pages), then paste the URL into https://www.pwabuilder.com and download the Android package.
- Or use Capacitor: `npm i @capacitor/core @capacitor/cli`, `npx cap init`, `npx cap add android`, copy this folder as the web dir, then build in Android Studio.

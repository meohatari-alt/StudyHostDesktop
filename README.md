# Study Buddy desktop

Tiny Windows wrapper (Tauri + WebView2) around your GitHub Pages site.

1. Edit `src-tauri/tauri.conf.json` -> change `url` to your real GitHub Pages address.
2. Push this folder to a GitHub repo (new repo, files at the root).
3. Actions tab -> "Build Windows exe" -> wait ~5-8 min -> download artifact `StudyBuddy-exe`.
4. Unzip, run `study-buddy.exe`. Pin it / make a shortcut.

Since it loads your live site, updating the site updates the app. No rebuild needed.

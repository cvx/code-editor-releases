# Code Editor — releases

Public distribution artifacts for Code Editor, a native macOS code editor.
The source lives in a separate private repository; this repo only holds built
releases and the update feed that GitHub Pages serves.

- **Download:** https://cvx.github.io/code-editor-releases/
- **Update feed (Sparkle appcast):** https://cvx.github.io/code-editor-releases/appcast.xml

Contents are generated — each release commit is written by `scripts/release.sh`
in the main repository (Developer ID signed, notarized, EdDSA-signed appcast).
Please don't edit files here by hand.

Requires Apple Silicon and macOS 26 or later.

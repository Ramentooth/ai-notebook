# My Notebook

A notebook that remembers what you've learned. Write after practice; AI quietly
summarizes each entry and can answer questions using only your own notes.

Single HTML file. No build step, no server, no accounts. Notes live in your
browser's localStorage; AI calls go directly from your device to the Anthropic API.

## Put it on your iPhone home screen

1. Host these files anywhere static — GitHub Pages works well:
   push this folder to a GitHub repo, then Settings → Pages → deploy from branch.
2. Open the page in Safari on your phone.
3. Share → **Add to Home Screen**. It opens fullscreen like an app.
4. In the app, tap **Enable AI · add key** and paste an Anthropic API key
   (console.anthropic.com). The key is stored only on your device.

Without a key everything still works — entry summaries fall back to your first
sentence, and the AI buttons explain what's missing.

## Backup

Tap **Export** on the home screen to download all notes as JSON.

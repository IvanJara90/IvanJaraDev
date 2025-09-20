# Gemini Notes

This file contains notes for the Gemini CLI agent to help with future interactions.

## Project Overview

- **Framework:** Hugo
- **Theme:** PaperMod
- **Deployment:** GitHub Pages at `https://ivanjara90.github.io/IvanJaraDev/`
- **Local Server:** Run `hugo server`. The site will be available at `http://localhost:1313/IvanJaraDev/`.

## Common Issues & Fixes

- **Posts not on homepage:** If blog posts don't appear on the homepage, `profileMode` is likely enabled in `hugo.toml`. To fix this, set `profileMode.enabled = false` to switch to "Regular Mode," which lists posts.
- **Local site not rendering correctly:** The site is served from the `/IvanJaraDev/` subdirectory due to the `baseURL` setting. Access it at `http://localhost:1313/IvanJaraDev/`.
- **Content display issues:** If content seems outdated or incorrect, the `public` directory might be stale. Delete the `public` directory (`rm -rf public`) and restart the `hugo server` to force a clean rebuild.

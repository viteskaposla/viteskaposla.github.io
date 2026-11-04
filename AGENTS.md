# Website development

The public GitHub Pages site is https://viteskaposla.github.io/ and publishes from the `main` branch.

- Make website drafts and design changes on `development`.
- Keep the existing Coming soon homepage on `main` while development continues.
- The rendered draft preview is https://viteskaposla.github.io/preview/.
- After editing `development/index.html`, refresh the preview copy at `preview/index.html` on `main`. Copy any future preview assets under `preview/` and keep their paths relative.
- For preview updates, change only files under `main/preview/`; preserve `main/index.html` exactly so the root page stays Coming soon.
- Keep the draft preview marked `noindex`; remove that directive from the final homepage when the user asks to launch.
- Merge into `main`, change the Pages publishing source, or publish the finished website only when the user asks to launch.

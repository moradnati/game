# game.moradnati.com

Public site for the games Netanel and Ariel make.

- `site/` is what Cloudflare Pages serves (build output directory: `site`, no build command).
- `site/SecondDawn/ArtStyle/` is the Second Dawn art archive. It is generated in the game repo
  (`Documents\second-dawn`, `tools/archive/README.md`). To update it, rebuild the archive there and copy
  `art/archive/site/*` over `site/SecondDawn/ArtStyle/`, then commit and push.
- Domain: game.moradnati.com (custom domain on the Cloudflare Pages project).

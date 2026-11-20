# Thirty-one formals

A tracker for visiting, and dining at a formal in, all 31 colleges of the University of Cambridge.

Live site: https://samuelgbaron.github.io/cambridge-formals/

- Tap the archway when you've visited a college, and the knife and fork when you've dined there.
- A college's coat of arms turns to full colour once you've dined there, and shows in grey if you've only visited.

## Where the list is saved

The list is saved in `progress.json` on the `data` branch of this repository. The site reads it from there, so every device shows the same list. Keeping it off `main` means saving a tick doesn't rebuild the site.

Anyone can view the list. To edit from a browser, connect that browser once with a fine-grained GitHub token. Instructions are at the bottom of the site. The token should have access to this repository only, with **Contents** set to **Read and write**. It's kept in that browser and only sent to GitHub.

Everything in the list, including notes, is public, because the repository is public.

The whole site is a single `index.html` with no build step.

## Credits

Coats of arms are from Wikipedia and Wikimedia Commons, where they are published under public-domain or Creative Commons licences. Founding dates are from Wikipedia's list of Cambridge colleges.

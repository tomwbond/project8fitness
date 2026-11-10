# Project 8 Fitness website

A one-page site for Project 8 Fitness, hosted free on GitHub Pages.

Everything is in `index.html`. There's no build step: edit the file, commit, and the live site updates within a minute or two.

## Making small changes

The easiest way is in your browser on GitHub: open `index.html`, click the pencil icon, make the change, then click **Commit changes**.

Look for comments starting `EDIT:` in `index.html`. They mark the bits you're most likely to change:

- **Class times and places**: the `Timetable` table. Each class is one row, starting `<tr>`.
- **Prices**: the `Prices` table, just below the timetable.
- **The eight ways**: the list in the `Eight ways we progress` section. Keep it to eight words, and short ones fit best around the 8.
- **Coach bios**: in the `Who coaches you` section.
- **Company details**: in the footer. Once Project 8 Fitness Ltd is registered, the company number and registered office need to go on the site.

## Colours

The colours are set at the top of the `<style>` block in `index.html`. The base is off-white and grey; `--splash` is the one accent colour, and `--on-splash` is the text colour that sits on it.

To try other accent colours in the browser, add `?colours` to the end of the address, for example `https://yourdomain.co.uk/?colours`. A small panel appears in the corner. Delete the tryout script at the bottom of `index.html` once you've chosen.

## Files

- `index.html`: the whole page
- `assets/logo.svg`: the logo used in the header. The 8 is built from eight segments, one for each of the eight ways, with one in the accent orange
- `assets/logo-reversed.svg`: the same logo in off-white, for dark backgrounds
- `assets/mark.svg`: the eight-segment 8 on its own
- `assets/favicon.svg`: the browser tab icon (the eight-segment 8 on a dark square)
- `assets/wordmark.svg` and `assets/wordmark-simple.svg`: the earlier text-only versions, kept for reference and no longer used on the site

The orange in the logo files is fixed at `#FF5B1A`. If you change `--splash`, change it in those files too.
- `assets/fonts/`: Barlow Condensed (headings) and Atkinson Hyperlegible Next (body text), both open-source and stored here so the site makes no third-party requests
- `notes/`: source material, not part of the live site

## Turning on GitHub Pages

1. In the repo, go to **Settings** > **Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose `main` and `/ (root)`, and click **Save**.
3. To use your own domain, type it under **Custom domain** and follow GitHub's instructions for the DNS records at your domain registrar. Tick **Enforce HTTPS** once it's available.

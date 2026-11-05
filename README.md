# Ezenwa Alphonsus Anayo | Personal Site

Markets. Technology. Possibilities.

A single-page personal site covering trading, Web3 and building. It is one self-contained file with no build step, no framework and no dependencies beyond Google Fonts.

Live site: https://ezenwa2003.github.io

## Files

```
index.html   the entire site (HTML, CSS and JavaScript)
README.md    this file
```

## Run it locally

Double-click `index.html` to open it in your browser. No server or install needed.

## Deploy free on GitHub Pages

1. Sign in to GitHub as `ezenwa2003` and click **New repository**.
2. Name it exactly `ezenwa2003.github.io`, set it to **Public**, and create it.
3. Click **uploading an existing file**, drag in `index.html` and `README.md`, then **Commit changes**.
4. Open **Settings**, then **Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, then **Save**.
5. Wait one to two minutes and visit https://ezenwa2003.github.io.

The file must be named `index.html` and sit at the root of the repository.

## Update the site

- On GitHub, open `index.html`, click the pencil icon, edit, and commit. The site refreshes in about a minute.
- Or upload a new `index.html` to the repository to replace the old one.

## Common edits

All content is plain HTML inside `index.html`.

- **Add a project:** in the `#lab` section, copy one `<article class="pj">` block. Change the title, description and tags. Point the GitHub button at the repository. When the project is ready, replace the disabled "View project" link (the one with `aria-disabled="true"`) with a real URL and remove that attribute.
- **Change colours:** edit the variables at the top of the `<style>` block. `--acc` is the green accent, `--bg` is the background.
- **Change contact details:** search for `anayoezenwa16@gmail.com` and `ezenwa2003` and update them.
- **Remove the custom cursor:** delete the `.cur` element near the top of `<body>` and the block commented `cursor` in the script.

## Custom domain (optional)

1. Buy a domain from a registrar.
2. Add four `A` records for the root domain: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`.
3. Add a `CNAME` record for `www` pointing to `ezenwa2003.github.io`.
4. In **Settings**, then **Pages**, enter the domain under **Custom domain** and save.
5. When the DNS check passes, enable **Enforce HTTPS**.

DNS changes can take from a few minutes to a day. If the IP addresses above ever change, GitHub's Pages documentation lists the current ones.

## Accessibility and motion

The site respects the system "reduce motion" setting, keeps visible keyboard focus rings, and uses touch targets of at least 44px. The custom cursor only appears on devices with a mouse.

## Contact

anayoezenwa16@gmail.com | https://github.com/ezenwa2003

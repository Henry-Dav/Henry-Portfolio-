# Portfolio — Email & Landing Page Copywriter

## Put it online with GitHub Pages (free, ~5 minutes)

1. Create a GitHub account at github.com if you don't have one.
2. Click **New repository**. Name it `portfolio`. Set it to **Public**. Create it.
3. On the repo page, click **Add file → Upload files**, and drag in ALL of these:
   - index.html
   - style.css
   - claude.html
   - hedra.html
   - taplio.html
   - capterra-manual.html
   - capterra-hiring.html
   - naturescout.html
4. Click **Commit changes**.
5. Go to **Settings → Pages**. Under "Branch", pick `main` and `/ (root)`. Save.
6. Wait about a minute, then refresh. Your link appears at the top:
   `https://YOURNAME.github.io/portfolio/`

That link is what you send people.

## Two things to change before you publish

Both are in `index.html`:

1. **Your email address.** Search for `hello@example.com` and replace it with your real one.
2. **The nav wordmark.** It currently reads "Email & Landing Page Copywriter" in the top left.
   If you'd rather it be your name, search for `nav-mark` and change the text between the tags.

## Want a custom domain later?

Buy a domain, then in Settings → Pages add it under "Custom domain". GitHub walks you through the DNS.

## Adding a new project

Copy any project page (e.g. `hedra.html`), rename it, swap the email copy inside the
`.before` and `.after` panels, then add a matching `<a class="card">` block to the grid
in `index.html`.

# ss-site

Static one-page site for **selfsounds.net**, served by GitHub Pages.

Standing rules for anyone touching this repo:

- **Commit author is always a non-personal identity:** the author name comes from the `ss-mp` account, and the author/committer email is always the account noreply address `353833369+ss-mp@users.noreply.github.com`. Never a personal name or personal email.
- **No secrets, drafts, or pipeline notes ever enter this repo.** Site source only.
- **Zero third-party assets** — system fonts, inline CSS, no analytics, no CDNs, no embeds.
- **One first-party inline `<script>`** is allowed and must never depend on anything external: the EN/PT language toggle (`#langbtn` + `[data-pt]` element swap, `localStorage` persistence, browser-language fallback). No libraries, no network.

Contact: `guiafonso@selfsounds.net`

Commit author/committer email is always the account noreply address (as enforced by GitHub email privacy).

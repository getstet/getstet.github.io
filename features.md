# stet — features

Every capability, grouped by what it does for you. All ship in the free, self-hosted package (Apache-2.0).

## Adopt

- **Auto Install** — Installs into your existing codebase. One command detects your framework and store, writes the registry and fallback, and leaves the first key rendering.
- **Copy scan** — Finds the copy your site already has. Finds the copy already in your components and adopts it — the rewrite touches only the leaf, printed as a diff first.
- **Stores** — Start without a database, add one later. Snapshot-only with no database, or plain Postgres in your own instance.
- **Framework support** — Works with Next.js, React, Astro and more. First-class Next.js, React and Astro; every other host reads the same committed bundle; a Python reader ships.
- **Migration** — Bring your content over from another CMS. One mapping file over your JSON or CSV export.

## Edit

- **Typed keys** — Your editor autocompletes every copy key. Every string is a typed key — a wrong key is a compile error, not a blank space in production.
- **Instant publish** — Fix a typo in seconds, no build needed. Publishing is a database transaction, not a build — the next request serves the new words.
- **Snapshot fallback** — Every string has a backup committed in your repo. Every key has a committed fallback, so a missing value or unreachable database never breaks a page.
- **Versioning** — Undo any change in one click. Every publish is kept; revert restores any prior wording without losing anything.
- **Content rules** — Guardrails on every field, checked at save. Character limits, a variable whitelist, advisory fit budgets — checked before anything is stored.
- **Environments** — Test copy in staging before it hits production. Each environment is a named store connection — never a copy of your data.
- **Promotion** — Preview exactly what will change before promoting. Staging to production with a dry run and conflict detection. (free · Cloud adds review)
- **Scheduling** — Set a date and time for any publish. Set the moment; the copy goes live without anyone awake. (free · Cloud runs it)
- **Review** — Changes wait for approval before going live. Every draft waits with its author recorded; approval is the publish. (free · Cloud adds policy)
- **Preview links** — Send clients a preview link, no account needed. A signed, expiring link renders the draft in place — reviewers never need a seat.
- **Workspace** — Run all your sites and apps from one place. Every site and app you run, listed and edited in one workspace.
- **Editor** — Editing without touching code or layout. A plain-labels editing UI that mounts as components into your own app's chrome — your auth, your theme tokens, no separate admin site. (free single-user · Cloud multi-user)

## Email

- **Email slots** — Editors change email text without breaking the design. Email copy as named slots on your own template.
- **Compliance gates** — Apply marketing rules so that your mail is always sent correctly. Marketing mail is blocked until the unsubscribe is in scope; a missing postal line warns.
- **Contacts** — Keep track of the contacts who are interested. Join and unsubscribe routes, consent provenance, a suppression list — in your own Postgres. (free · Cloud hosts)
- **Broadcasts** — Send group emails to your customer list. Linted before it goes, with per-recipient send records. (free · Cloud supersedes)

## SEO

- **SEO** — Edit titles and descriptions like any other copy. The fields that decide how you appear are ordinary keys — versioned, publishable. Catches SEO mistakes before they go live: eight offline rules — missing descriptions, duplicate titles, over-length, canonical→noindex, markup-vs-content, alt text.
- **Structured data** — Structured data that stays in sync with your pages. Markup bound to the keys that render on the page.

## Agents

- **MCP** — Connect Claude or any agent over MCP. An MCP server with stet_* tools — assistants read and propose copy without screen-scraping your admin.
- **Agent guardrails** — Scope your agent behind an approval wall, or allow it to yolo. Everything an agent writes is a draft with its author recorded; brand keys are locked entirely.

## Leave

- **Committed snapshot** — A full copy of your content lives in your repo. A complete, buildable copy of every string, at every moment.
- **Eject** — One command removes stet and keeps your content. Writes everything back, exports history, removes the mount.
- **Open source** — Free to self-host, with everything included. Self-hosted is the whole mechanism, not a trial — Cloud sells hosting, identity and review.

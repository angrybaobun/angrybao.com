# angrybao.com

The public website for Angry Bao, a London worldbuilding studio.

Right now this is a single holding page: `index.html` (also served as `404.html`), with `favicon.svg`.
It is plain HTML, CSS and JavaScript with no build step, so the repository root is deployed as-is.

## Hosting

Hosted on Cloudflare Pages, connected to this repository. Every push to `main` deploys automatically.

- Build command: none
- Output directory: `/` (repository root)
- `_headers` sets basic security headers.

## Email sign-up

The sign-up form posts to a mailing-list provider. Set `SIGNUP_URL` near the bottom of `index.html`
to the provider's form address. While it is empty, the form tells visitors that sign-ups open soon.

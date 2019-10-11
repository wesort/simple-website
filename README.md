# Simple website
The basic modern website. No build process. Minimal config. Host on Netlify, GitHub Pages or (probably) any server.

## Features
- Static site
- Lightweight, fast, responsive
- Custom 404 error page with meta-refresh to homepage after 3 seconds
-

## Setup
- [ ] Clone this repo to your local environment
- [ ] Open `index.html` in a browser or do whatever you do to get to this step

## Customise
- [ ] Page content: everything within `.wrap` div
- [ ] Meta tags with search & social optimisation: A tool like megatags.co can be useful
- [ ] Styles: `background-color`, `color`, hyperlink style
- [ ] Favicon / Icons: either supply one or use something like [favicon.io](https://favicon.io/)
- [ ] Google Analytics: setup account and tracking code, insert into bottom of `index.html`
- [ ] For the sake of typography, you could add a `&nbsp;` (none breaking space) in the final space (between two short words) in each paragrah. This is done to avoid&nbsp;widows.


## Deploy on own server
- [ ] Place the files on the server and connect your domain
- [ ] Remove `.html` file extension with [this gist for Nginx](https://gist.github.com/wesort/a10c1d6edf62bc693fb7015cdd0dde2a) or [this gist for Apache]()

## Deploying to Netlify
- [ ] Visit [app.netlify.com](https://app.netlify.com/) or start a (free) account
- [ ] Create a new site by connecting to GitHub: [app.netlify.com/start](https://app.netlify.com/start)
- [ ] Robots: Netlify will rename `live.robots.txt` to `robots.txt` automatically from the `netlify.toml` build command
- [ ] Redirect: `_redircts` file allows for legacy or vanity URLs to be redirected appropriately



# Simple website
The basic modern website. No build process. Minimal config. Host on Netlify, GitHub Pages or (probably) any server.

## Demo
[simple.wesort.co.uk](http://simple.wesort.co.uk)

## Examples of similar sites
- [wesort.co.uk/simple](https://wesort.co.uk/simple)

## Features
- Static site with no dependencies or build process
- Lightweight, fast, responsive
- Apply any styles. Choices of typeface and colour go a long way to expressing a brand indentity.
- Shallow learning curve
- Widest possible options for hosting
- Search and social optimisable
- Custom 404 error page with meta-refresh to homepage after 3 seconds
- All external links open in new tab / window (uses vanilla javascript)

## Setup
- [ ] Clone or download this repo
- [ ] Open `index.html` in a browser

## Customise
- [ ] Visible page content: everything within `.wrap` div
  - [ ] You'll likely want to explain what you do, how you do it, and why you're the best at doing it. This might include links to lead visitors to more information.
  - [ ] A few social icons are ready to use (via [Simple Icons](https://simpleicons.org/))
  - [ ] For the sake of typography, you could add a `&nbsp;` (none breaking space) in the final space (between two short words) in each paragrah. This is done to avoid [widows](https://practicaltypography.com/widow-and-orphan-control.html)
- [ ] Styles: `font-family`, `background-color`, `color`, hyperlink styles
  - [ ] CSS is set as a `<style>` tag within `index.html` for simplicity. However, these could be moved to an external stylesheet if multiple pages are being created. A `<link>` tag is included but commented out.
  - [ ] Be sure to adjust styles in ` 404.html` and within the each social icon file being used
- [ ] Favicon / Icons: either supply one or use something like [favicon.io](https://favicon.io/)
- [ ] Meta tags for search & social optimisation
  - [ ] A tool like [megatags.co](https://megatags.co) can be useful
  - [ ] Create an image for social media rich cards (1280 × 640px is a good size)
- [ ] Google Analytics: setup account and tracking code, insert into bottom of `index.html`
- [ ] If you are including video embed, [fitvidsjs](http://fitvidsjs.com/) will be very useful and will need to be installed

## Deploy to Netlify
- [ ] Start a [Netlify.com](https://app.netlify.com/) account (free)
- [ ] Create a new site by connecting to GitHub: [app.netlify.com/start](https://app.netlify.com/start)
- [ ] Configure the domain:
    - [ ] Set the subdomain to something suitable for the project
    - [ ] Configure your custom domain ([help doc](https://www.netlify.com/docs/custom-domains))
- [ ] Robots: Netlify will rename `live.robots.txt` to `robots.txt` automatically with a build command in `netlify.toml`
- [ ] Redirect: `_redircts` file allows for legacy or vanity URLs to be redirected appropriately

## Deploy to GitHub Pages
- [ ] More info: [pages.github.com](https://pages.github.com/)
- [ ] Configure the custom domain ([help doc](https://help.github.com/en/articles/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain))

 
## Deploy on own server
- [ ] Place the files on the server and connect your domain
- [ ] Remove `.html` file extension with [this gist for Nginx](https://gist.github.com/wesort/a10c1d6edf62bc693fb7015cdd0dde2a) or [this gist for Apache](https://gist.github.com/wesort/645e3f54ca35ac6abcdd100c0f24d2ad)
-

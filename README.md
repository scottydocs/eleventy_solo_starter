# Eleventy starter set

This is a starter set for the [Eleventy](https://11ty.dev) [static site generator (SSG)](https://staticgen.com), based on my website at [brycewray.com](https://brycewray.com). Please note that this serves just as an example; my **real** site repo is [eleventy_solo](https://github.com/brycewray/eleventy_solo).

See the [online demo](https://eleventy-solo-starter.netlify.app/).

## How to use

1. Clone this to a local repo.
2. Make appropriate changes to `/_data/metadata.json` and `_data/siteparams.json` to conform to your site’s parameters.
3. Run `npm install` to load all the dependencies in `package.json`, which includes Eleventy.
4. Run `npm run start` from your terminal app. You can then view the site in [http://localhost:3000](http://localhost:3000) on your computer.
5. Read the sample posts and their Markdown files to see how everything works.
6. Edit the content to make it your own!
7. When ready, [deploy the site](https://www.11ty.dev/docs/tutorials/#put-it-on-the-web) to your chosen host.

## What’s under the hood

- Lazy-loading of some images through use of [lazyload](https://github.com/verlok/vanilla-lazyload).
- Responsive images through my run-time `imgxfm.js` script and the `lazypicture` shortcode. (The **real** site repo now uses [Cloudinary](https://cloudinary.com) rather than the run-time script.)
- [PostCSS](https://postcss.org) and [Tailwind CSS](https://tailwindcss.com).
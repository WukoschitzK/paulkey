# Portfolio Website using Statamic CMS

## Features
- Articles blogging collection with most recent articles on the home page
- Topics taxonomy for Articles
- Pages structure for dynamic navigation
- Customizable social links and icons
- Clean & modern typography using [Inter](https://rsms.me/inter/)
- Beautifully responsive
- Built with [TailwindCSS](https://tailwindcss.com)
- Itty bitty [Alpine.js](https://github.com/alpinejs/alpine) for interactions
- 💯/💯/💯/💯 Lighthouse score


## Quick Start

### 1. Create a new site

You can create a new site using the [Statamic CLI Tool](https://github.com/statamic/cli):

```
statamic new your-site statamic/starter-kit-cool-writings
```

Or you can install manually into a fresh [Statamic installation](https://statamic.dev/installation) by running:

```
php please starter-kit:install statamic/starter-kit-cool-writings --clear-site
```

### 2. Make a new user

The above installers should prompt you to make a user, but you can also run `php please make:user`. You'll want it to be a `super` so you have access to everything.

### 3. Recompile the CSS (optional)

```
npm i && npm run dev
```

To compile for production again:

```
npm run build
```

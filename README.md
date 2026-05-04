# Religious Stuides RSS Aggregator [RS-RSS.com](https://rs-rss.com)
[![Netlify Status](https://api.netlify.com/api/v1/badges/58a6c39a-f478-4a62-813a-bae8dad5ea39/deploy-status)](https://app.netlify.com/sites/rs-rss/deploys)
[![Update site](https://github.com/adamdjbrett/rs-rss.com/actions/workflows/scheduled_build.yml/badge.svg)](https://github.com/adamdjbrett/rs-rss.com/actions/workflows/scheduled_build.yml)

## [Multiplicity - RSS Aggregator Starter Based On Eleventy](https://github.com/lwojcik/eleventy-template-multiplicity)

[**Multiplicity** (abbreviated as 'm10y')](https://github.com/lwojcik/eleventy-template-multiplicity) by [@lwojcik](https://github.com/lwojcik/) is a simple starter pack based on [Eleventy static site generator](https://11ty.dev) that allows you to create RSS aggregator site.

Alongside the template code, it also contains a GitHub action required to keep the site up to date.

[View demo](https://eleventy-m10y.lkmt.us/)

Want to see in in action? Check out [Blogworm.eu](https://blogworm.eu/).

### Instant deploy

Netlify:

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/lwojcik/eleventy-template-multiplicity)

Vercel:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/lwojcik/eleventy-template-multiplicity)

Render:

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/lwojcik/eleventy-template-multiplicity)

### Features

- light / dark mode switcher + honoring color scheme preference
- pagination
- translation ready (separate file with static phrases)
- automatic favicon generation
- support for RSS and JSON feeds
- custom avatar alongside each feed item

### Setup and personalization

1. Fork the repository.
2. Configure the site according to your preferences - see [`siteConfig.js`](./content/_data/siteConfig.js) and template files.
3. Modify the list of feeds you want to aggregate - they are located in [`content/sites`](./content/sites/).
   1. Each site has the following properties:
      - `name` - name of the site
      - `url` - URL of the site
      - `avatar` - image to display alongside the site name (e.g. favicon). During the build process the image will be downloaded, resized and served locally
      - `feed` - URL of the RSS or JSON feed to fetch articles from
      - `hideFromSiteList` - set it to `true` if you want to hide this site from the list of sites on the Sites page. It is useful if you want to add two sites with different RSS feeds under the same name and avoid seeing duplicates on the list
4. Deploy the site to Netlify or Vercel
5. Set up the GitHub action in [`.github/workflows/scheduled_build.yml`](./.github/workflows/scheduled_build.yml):
   1. Create a build hook URL and save it as a GitHub secret in your repository - e.g. `NETLIFY_BUILD_HOOK_URL` or `VERCEL_BUILD_HOOK_URL`
6. Done! Your aggregator is up and running.

### Translation file

See [`phrases.js`](./content/_data/phrases.js) for the list of translatable static phrases.

### Note for Netlify users

The aggregator uses [eleventy-fetch](https://www.11ty.dev/docs/plugins/fetch/) plugin for fetching and caching network requests. If you use Netlify, you can limit number of network requests with Netlify cache mechanism - [see Eleventy docs on how to enable it](https://www.11ty.dev/docs/plugins/fetch/#running-this-on-your-build-server).

### Contributions

Contributions of the following kind are welcome:

- bug reports / fixes
- feature suggestions / improvements of existing features

Before contributing be sure to read [Code of Conduct](./CODE_OF_CONDUCT.md).
Ran successfully 2026-03-04 08:08:12
Ran successfully 2026-03-05 08:09:22
Ran successfully 2026-03-06 08:07:35
Ran successfully 2026-03-07 08:04:21
Ran successfully 2026-03-08 08:04:53
Ran successfully 2026-03-09 08:11:39
Ran successfully 2026-03-10 08:09:35
Ran successfully 2026-03-11 08:09:53
Ran successfully 2026-03-12 08:11:07
Ran successfully 2026-03-13 08:10:34
Ran successfully 2026-03-14 08:06:24
Ran successfully 2026-03-15 08:08:58
Ran successfully 2026-03-16 08:21:22
Ran successfully 2026-03-17 08:13:36
Ran successfully 2026-03-18 08:13:03
Ran successfully 2026-03-19 08:11:32
Ran successfully 2026-03-20 08:10:41
Ran successfully 2026-03-21 08:05:20
Ran successfully 2026-03-22 08:06:16
Ran successfully 2026-03-23 08:18:05
Ran successfully 2026-03-24 08:13:49
Ran successfully 2026-03-25 08:13:21
Ran successfully 2026-03-26 08:16:30
Ran successfully 2026-03-27 08:14:11
Ran successfully 2026-03-28 08:09:49
Ran successfully 2026-03-29 08:10:12
Ran successfully 2026-03-30 08:30:47
Ran successfully 2026-03-31 08:21:44
Ran successfully 2026-04-01 08:26:24
Ran successfully 2026-04-02 08:20:31
Ran successfully 2026-04-03 08:16:40
Ran successfully 2026-04-04 08:10:48
Ran successfully 2026-04-05 08:10:43
Ran successfully 2026-04-06 08:30:39
Ran successfully 2026-04-07 08:25:03
Ran successfully 2026-04-08 08:24:09
Ran successfully 2026-04-09 08:30:09
Ran successfully 2026-04-10 08:29:51
Ran successfully 2026-04-11 08:11:10
Ran successfully 2026-04-12 08:16:13
Ran successfully 2026-04-13 08:40:47
Ran successfully 2026-04-14 08:33:00
Ran successfully 2026-04-15 08:32:59
Ran successfully 2026-04-16 08:33:09
Ran successfully 2026-04-17 08:32:33
Ran successfully 2026-04-18 08:13:12
Ran successfully 2026-04-19 08:19:21
Ran successfully 2026-04-20 08:44:08
Ran successfully 2026-04-21 08:35:28
Ran successfully 2026-04-22 08:34:01
Ran successfully 2026-04-23 08:34:49
Ran successfully 2026-04-24 08:39:56
Ran successfully 2026-04-25 08:18:44
Ran successfully 2026-04-26 08:25:39
Ran successfully 2026-04-27 08:49:40
Ran successfully 2026-04-28 08:48:06
Ran successfully 2026-04-29 08:45:04
Ran successfully 2026-04-30 08:45:08
Ran successfully 2026-05-01 08:38:17
Ran successfully 2026-05-02 08:29:38
Ran successfully 2026-05-03 08:33:34
Ran successfully 2026-05-04 08:48:44

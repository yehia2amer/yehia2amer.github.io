# Software & Beyond
A simple blog theme focused on writing powered by Bulma and Zola.

![Software & Beyond](./screenshot.png)

## Live Demo
Live version of the website is available at [here](https://yehia2amer.github.io/)

## Installation
Get [Zola](https://www.getzola.org/) and follow their guide on [installing a theme](https://www.getzola.org/documentation/themes/installing-and-using-themes/).
Make sure to add `theme = "Software & Beyond"` to your `config.toml`

**Check zola version (only 0.9.0+)**
Just to double-check to make sure you have the right version. It is not supported to use this theme with a version under 0.9.0.

## How to serve?
Go into your sites directory, and type `zola serve`. You should see your new site at `localhost:1111`.

## Deployment
[Zola](https://www.getzola.org) already has great documentation for deploying to [Netlify](https://www.getzola.org/documentation/deployment/netlify/) or [Github Pages](https://www.getzola.org/documentation/deployment/github-pages/). I won't bore you with a regurgitated explanation.

## Theme Options
```toml
# Add links to favicon, you can use https://realfavicongenerator.net/ to generate favicon for your site
[extra.favicon]
favicon_16x16 = "/icons/favicon-16x16.png"
favicon_32x32 = "/icons/favicon-32x32.png"
apple_touch_icon = "/icons/apple-touch-icon.png"
safari_pinned_tab = "/icons/safari-pinned-tab.svg"
webmanifest = "/icons/site.webmanifest"

# Author details
[extra.author]
name = "Software & Beyond"
avatar = "/images/avatar.png"

# Social links
[extra.social]
facebook = "<facebook_username>"
github = "<github_username>"
keybase = "<keybase_username>"
linkedin = "<linkedin_username>"
stackoverflow = "<stackoverflow_userid>"
twitter = "<twitter_username>"

# To add google analytics
[extra.analytics]
google = "<your_gtag>"

# To add hyvor comments
[extra.commenting]
hyvor = "<your_hyvor_website_id>"

# To enable mapbox maps
[extra.mapbox]
access_token = "<your_access_token>"
```

## Features
- [x] Dark Mode
- [x] Pagination
- [x] Search
- [x] Charts
- [x] Maps
- [x] Diagrams
- [x] Galleria
- [x] Analytics
- [x] Comments
- [x] Categories
- [x] Social Links
- [x] Post Sharing

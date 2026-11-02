# apps.bananaloop.com

GitHub Pages site for `apps.bananaloop.com`, the developer website on the Banana Loop App Store listings.

- `app-ads.txt`: the authorized ad sellers file that AdMob crawls. bananaloop.com is a WordPress.com Personal site and can't serve files at its root, so this file lives here instead.
- `index.html`: forwards visitors to https://bananaloop.com/apps/.

When an app adds an ad network, add that network's line to `app-ads.txt`.

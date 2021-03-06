## Migrating to Essential Next.js Plugin

This guide is to assist `next-on-netlify` users in their migration to Netlify's [Essential Next.js Build Plugin](https://github.com/netlify/netlify-plugin-nextjs).

Please visit [this issue](https://github.com/netlify/next-on-netlify/issues/176) to ask questions about migrating and/or the deprecation of `next-on-netlify`.

### Existing NoN users

1. [Uninstall](https://docs.npmjs.com/uninstalling-packages-and-dependencies) `next-on-netlify`.
2. Remove the `"postbuild": "next-on-netlify"` script from your `package.json`.
3. Get the Essential Next.js plugin.
    - For new Next.js sites on Netlify, the plugin will be automatically installed. You can [opt out of the plugin](https://docs.netlify.com/configure-builds/build-plugins/#remove-a-plugin) by visiting the **Plugins** tab for your site in the Netlify UI.
    - For existing sites on Netlify, follow the manual installation instructions in the [plugin README](https://github.com/netlify/netlify-plugin-nextjs#installation-and-configuration), which explains UI-based and file-based installation.

### Brand New Users

Deploy a new Next.js site to Netlify! Your site will automatically build with the plugin. You can [opt out of the plugin](https://docs.netlify.com/configure-builds/build-plugins/#remove-a-plugin) by visiting the **Plugins** tab for your site in the Netlify UI.

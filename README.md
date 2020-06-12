# Gatsby Theme Web Monetization — Basic Example

_Basic usage example of [gatsby-theme-web-monetization](https://github.com/ekafyi/gatsby-theme-web-monetization/) for a blog site._

[🔗 Demo](http://gtwm-example-blog.netlify.app)

[🛠 Step-by-step post on how I add the theme to this site](https://gist.github.com/ekafyi/fbd138a4d97ad2cb1c77dd476ad37500)

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/ekafyi/gatsby-starter-web-monetization-theme-blog)

---

## How to use


1. Clone [the starter site](https://github.com/ekafyi/gatsby-starter-web-monetization-theme-blog) to make a new site from this example
	* …or use the Gatsby CLI, `gatsby new my-monetized-site https://github.com/ekafyi/gatsby-starter-web-monetization-theme-blog`
	* …or use the Netlify deploy button above
2. Add your payment pointer in `gatsby-config.js`
3. Add your content in `content`
4. ??
5. Profit

Head to the themes’ documentation for more information about their usage:
- [gatsby-theme-web-monetization](https://github.com/ekafyi/gatsby-theme-web-monetization)
- [gatsby-theme-blog](https://github.com/gatsbyjs/gatsby/tree/master/packages/gatsby-theme-blog)
- [gatsby-theme-notes](https://github.com/gatsbyjs/gatsby/tree/master/packages/gatsby-theme-notes)

## ⚠️ Warning

This example serves as an MVP which aims to demonstrates how the Web Monetization API works.

Wrapping your “exclusive” (monetized-only) content in the `IfWebMonetized` component _is not secure_. The content still gets sent, just not rendered; it will be easy for tech-savvy visitors to find it. Don’t use it for sensitive data, and consider using serverless/cloud functions for better security.

Also, make sure your source code (eg. Github repository) is set to private. 😬

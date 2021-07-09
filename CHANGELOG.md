## 0.2.2 (2021-07-08)

### Fix

- 📸 updated BannerImage component to use Imgix to source images
- **post**: 🔧 added prerender to post
- **post**: ✅ linted files and fixed some typos
- **post**: 🔧 removed prerender
- **bannerimage**: 💄 tweaked css to avoid CLS
- 📸 linked blog post images to imgix sources
- **gitignore**: ✅ typo
- **dependencies**: 💫 updated packages

### Refactor

- 🏄🏽‍♂️ removed npm-lockfile sinceusing pnpm now

## 0.2.1 (2021-07-05)

### Fix

- 🚧 revert back to report only csp
- **service-worker**: ✅ fixed typo
- 🔧 removed optional chaining in website config file

## 0.2.0 (2021-07-05)

### Feat

- **pwa**: ✨ added pwa capability
- **error**: ⛔️ added default 404 page

### Fix

- **dependencies**: 💫 upgrade packages
- **dependencies**: 💫 update package
- **dependencies**: 💫 update packages

## 0.1.0 (2021-06-24)

### Fix

- 🤖 updated for better SEO integration
- **dependencies**: 💫 update package
- **dependencies**: 💫 update package:
- **styles**: 💄 added style optimsation for touch screen
- **dependencies**: 💫 update packages:
- **layout**: 🐞 ironed out another issue with layout template for non blog post pages
- **package.json**: reset server ports to 3000
- **layout**: 🐞 fixed call of blog post data in layout for non blog-post
- **dependencies**: 💫 update packages
- **dependencies**: 💫 update packages:
- **dependencies**: 💫 update package
- 🔥 optimised scss prepend data only adding varaibles
- 🔥 optimised CSS removing unused selectors
- **Icon**: 🔥 optimised import of icons
- 💫 updated packages
- **package.json**: reset dev and preview server ports to 3000
- **static**: 🤖 added robots.txt
- 🤗 corrected a11y atribute
- 🔧 made all blog posts static
- 💫 added hooks
- **dependencies**: 💫 update package
- **hooks**: 🚧 remove hooks for debugging
- **blogpostsummary**: 🐞 logic fix
- **index**: 🚧 debugging
- **hooks**: 🔐 debugging csp
- **package.json**: 🚧 dev deps to deps
- **hooks**: 🚧 set CSP to report only
- 🚧 temporarily remove security headers
- **index**: 🔧 changed error behaviour
- **rodneylabcredit**: ✅ fixed typo
- **routes**: 🔧 improved robustness
- **hooks**: ✅ fixed typo
- **netlify**: 🔧 updated netlify.toml
- 🔧 set node version to 12.20
- 🔧 updated netlify.toml
- **routes/slug.json**: 🔧 improved code robustness
- **index**: 🤖 added metadecsription
- **hooks**: ✅ updated config
- **post**: 🖋 removed "blog" from blog post paths

### Refactor

- 🛁 moved blog posts from src/content to src/routes for better integration with svelteKit and improved handling of mdsvex
- **styles**: 🛁 removed all variables from global styles and included in separate file

### Feat

- ✨ added some examples to hooks.js for CSP policy
- **routes/slug**: ✨ prerendering blog posts
- **index**: ✨ prerendering home page
- 🔐 added HTTP security headers
- **bannerimage**: 📸 added responsive banner image component
- **bannerimage**: 📸 added responsive banner image component
- 💄 added styling

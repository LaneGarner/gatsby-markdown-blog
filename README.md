Basic Gatsby blog template using markdown files to create blog posts

## Instructions

* npm i
* create .env.development at root with: 
  * GATSBY_GRAPHQL_IDE=playground
  * GATSBY_SITE_RECAPTCHA_KEY=
* when connecting to github ci on netlify run `git config core.ignorecase false`
* add env variables to netlify
  * GATSBY_SITE_RECAPTCHA_KEY
  * GATSBY_SITE_RECAPTCHA_SECRET
  * SITE_RECAPTCHA_KEY
  * SITE_RECAPTCHA_SECRET
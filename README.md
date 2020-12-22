# nuxt-multiline-style

##
Index page contains 3 nested divs with the same multiline style attribute.

On ssr load, inspect the nested divs and notice how only the parent div's style has been parsed correctly, while the nested children's style is broken by the \n charecter.

Use the links to navigate back and forth between index page and its copy, and you will notice that style is parsed correctly  when client side rendered.

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

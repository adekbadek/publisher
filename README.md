# publisher

A static-site blog generated with [hugo](https://gohugo.io), with posting to medium.com with [markdown-to-medium](https://github.com/yoshuawuyts/markdown-to-medium)

## how to

1. `$ npm i` to install dependencies
1. `$ npm run dev` to start hugo dev server and sass parsing with gulp
1. `$ npm run build` to build static files (to `/public`)
1. `$ npm run medium path/to/file.md` to publish to medium. First time will need `--token` passed.

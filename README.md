# inversion-engine.github.io

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

Github pages repo for https://inversion-engine.com

## How does this help with [Building the World Computer](https://inversion-engine.com)?

The https://inversion-engine.com website helps get the word out about the project, and hopefuly generates understanding and clarity about the goals / roadmap of Inversion Engine itself.

## How to work with this repo

We're currently using mdbook + github pages to host the site.

Develop the book:

```shell
cd ./book
mdbook serve
# point browser to the link that is output
# edit markdown files in ./book/src
```

Build the book:

```shell
cd ./book
mdbook build
```

Publish the site:

```shell
git commit -a -m "your message"
git push
```

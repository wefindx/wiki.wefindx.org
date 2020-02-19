# README

This is the [repository](https://github.com/wefindx/wiki.wefindx.org) of concepts and definitions, and collaboratively edited using [GitBook](https://www.npmjs.com/package/gitbook) toolkit.

Publishing is done by commiting statics to `gh-pages` branch which auto-publishes to [wiki.wefindx.org](https://wiki.wefindx.org).

# USAGE
Simply edit `.md` files, and make pull requests. Index is generated from `SUMMARY.md`.

# INSTRUCTIONS
Use [gitbook-cli](https://www.npmjs.com/package/gitbook), and do `gitbook serve` to live-reload preview, like so:

```
# Prerequisite
gitbook --version
 CLI version: 2.3.2
 GitBook version: 3.2.3

git clone git@github.com:wefindx/wiki.wefindx.org.git
cd wiki.wefindx.org
gitbook install
gitbook serve
```

# PUBLISHING
Use commands like described in `./publish.sh` file. (feel free to suggest simpler/better way)

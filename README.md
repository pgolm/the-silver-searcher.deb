# the-silver-searcher.deb

Debian packaging files for [the\_silver_searcher](https://github.com/ggreer/the_silver_searcher)

Launchpad PPA: [https://launchpad.net/~pgolm/+archive/the-silver-searcher](https://launchpad.net/~pgolm/+archive/the-silver-searcher)

## How To install it in Ubuntu 13.04:

```bash
sudo add-apt-repository ppa:pgolm/the-silver-searcher
sudo apt-get update
sudo apt-get install the-silver-searcher
```

## Build Package

```bash
git buildpackage -S --git-upstream-tree=FETCH_HEAD -i.git     
```

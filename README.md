A repo which is used to show/deploy Artsy's static sock page based on the artwork

Basically I edited an artwork page from Artsy in chrome, downloaded the resulted code and shipped it
to a static site generator.

```sh
#clone
git clone https://github.com/orta/socks-site
cd socks-site
yarn install

# dev
yarn serve

# deploy
yarn now
yarn alias [url from ^] artsy-socks
```

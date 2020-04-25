# Haskell web frameworks

## Requirements

* has to work with GHCJS
* has to be type-safe
* will use Haskell to generate: JS, HTML and CSS
* has to scale to huge amount of traffic

Web frameworks or libraries:

* [miso](http://hackage.haskell.org/package/miso)
* [yesod](http://hackage.haskell.org/package/yesod)
* [snap](http://hackage.haskell.org/package/snap)
* [scotty](http://hackage.haskell.org/package/scotty)
* [servant](http://hackage.haskell.org/package/servant)
* [growler](http://hackage.haskell.org/package/growler)
* [reflex](http://hackage.haskell.org/package/reflex)
* [Wheb](http://hackage.haskell.org/package/Wheb)
* [warp](http://hackage.haskell.org/package/warp)
* [wai](http://hackage.haskell.org/package/wai)
* [react-haskell](http://hackage.haskell.org/package/react-haskell)
* [blaze-html](http://hackage.haskell.org/package/blaze-html)
* [reflex](http://hackage.haskell.org/package/reflex) + [obelisk](https://github.com/obsidiansystems/obelisk)
* [Spock](http://hackage.haskell.org/package/Spock)
* [magicbane](http://hackage.haskell.org/package/magicbane)
* [happstack-server](http://hackage.haskell.org/package/happstack-server)
* [happstack-lite](http://hackage.haskell.org/package/happstack-lite)
* [nested-routes](http://hackage.haskell.org/package/nested-routes)
* [apiary](http://hackage.haskell.org/package/apiary)
* [miku](http://hackage.haskell.org/package/miku)
* [mohws](http://hackage.haskell.org/package/mohws)
* [salvia](http://hackage.haskell.org/package/salvia)
* [MFlow](http://hackage.haskell.org/package/MFlow)
* [webapi](http://hackage.haskell.org/package/webapi)
* [req](http://hackage.haskell.org/package/req)

Best options:

* ✔ miso + servant -> miso is very simple, performant and featureful. Combined with servant, it's a full-stack solution
* yesod - has cases in which is inflexible

## compile to HTML framework or libraries:

* XHTML [xhtml](http://hackage.haskell.org/package/xhtml)
* Blaze [blaze-html](http://hackage.haskell.org/package/blaze-html) - improves on XHTML?
* Lucid [lucid](http://hackage.haskell.org/package/lucid) - improves on Blaze? - [tutorial](https://chrisdone.com/posts/lucid/)
* Nice HTML [nice-html](http://hackage.haskell.org/package/nice-html)
* Type of HTML [type-of-html](http://hackage.haskell.org/package/type-of-html)

Best option:

* ✔ Lucid [](http://hackage.haskell.org/package/lucid) - improves on Blaze? - [tutorial](https://chrisdone.com/posts/lucid/)


## Compile to CSS framework or libraries

* Cassius and Lucius [](http://hackage.haskell.org/package/shakespeare-css)
* Clay [](http://hackage.haskell.org/package/clay) - [tutorial](http://fvisser.nl/clay/)

Best option:

* ✔ Clay [](http://hackage.haskell.org/package/clay) - [tutorial](http://fvisser.nl/clay/)

## Compile to JS framework or libraries

* GHCJS [ghcjs-base](http://hackage.haskell.org/package/ghcjs-base)
* Haste [haste-compiler](http://hackage.haskell.org/package/haste-compiler)
* Fay [fay](http://hackage.haskell.org/package/fay)

Best option:

* ✔ GHCJS [ghcjs-base](http://hackage.haskell.org/package/ghcjs-base)
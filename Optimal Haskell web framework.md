## Requirements:

* has to work with GHCJS
* has to be type-safe
* will use Haskell to generate: JS, HTML and CSS
* has to scale to huge amount of traffic

Web frameworks or libraries:

* http://hackage.haskell.org/package/miso
* http://hackage.haskell.org/package/yesod
* http://hackage.haskell.org/package/snap
* http://hackage.haskell.org/package/scotty
* http://hackage.haskell.org/package/servant
* http://hackage.haskell.org/package/growler
* http://hackage.haskell.org/package/reflex
* http://hackage.haskell.org/package/Wheb
* http://hackage.haskell.org/package/warp
* http://hackage.haskell.org/package/wai
* http://hackage.haskell.org/package/react-haskell
* http://hackage.haskell.org/package/blaze-html
* http://hackage.haskell.org/package/reflex + https://github.com/obsidiansystems/obelisk
* http://hackage.haskell.org/package/Spock
* http://hackage.haskell.org/package/magicbane
* http://hackage.haskell.org/package/happstack-server
* http://hackage.haskell.org/package/happstack-lite
* http://hackage.haskell.org/package/nested-routes
* http://hackage.haskell.org/package/apiary
* http://hackage.haskell.org/package/miku
* http://hackage.haskell.org/package/mohws
* http://hackage.haskell.org/package/salvia
* http://hackage.haskell.org/package/MFlow
* http://hackage.haskell.org/package/webapi
* http://hackage.haskell.org/package/req


Best options:

* ✔ miso + servant -> miso is very simple, performant and featureful. Combined with servant, it's a full-stack solution
* yesod - has cases in which is inflexible

## Optimal compile to HTML framework or library:

* XHTML http://hackage.haskell.org/package/xhtml
* Blaze http://hackage.haskell.org/package/blaze-html - improves on XHTML?
* Lucid http://hackage.haskell.org/package/lucid - improves on Blaze? - [tutorial](https://chrisdone.com/posts/lucid/)

Best option:

* ✔ Lucid http://hackage.haskell.org/package/lucid - improves on Blaze? - [tutorial](https://chrisdone.com/posts/lucid/)


## Optimal compile to CSS framework or library:

* Cassius and Lucius http://hackage.haskell.org/package/shakespeare-css
* Clay http://hackage.haskell.org/package/clay - [tutorial](http://fvisser.nl/clay/)

Best option:

* ✔ Clay http://hackage.haskell.org/package/clay - [tutorial](http://fvisser.nl/clay/)

## Optimal compile to JS framework or library:

* GHCJS http://hackage.haskell.org/package/ghcjs-base
* Haste http://hackage.haskell.org/package/haste-compiler
* Fay http://hackage.haskell.org/package/fay

Best option:

* ✔ GHCJS http://hackage.haskell.org/package/ghcjs-base
data-or
=======
[![Hackage version](https://img.shields.io/hackage/v/data-or.svg?style=flat)](https://hackage.haskell.org/package/data-or) 
[![Build Status](https://github.com/wrengr/data-or/workflows/ci/badge.svg)](https://github.com/wrengr/data-or/actions?query=workflow%3Aci)
[![Dependencies](https://img.shields.io/hackage-deps/v/data-or.svg?style=flat)](http://packdeps.haskellers.com/specific?package=data-or)

This package provides a data type for non-exclusive disjunction.
In addition we provide a non-truncating version of `zip`, `zipWith`,
etc.


## Install

This is a simple package and should be easy to install. You should
be able to use one of the following standard methods to install it.

    -- With cabal-install and without the source:
    $> cabal install data-or
    
    -- With cabal-install and with the source already:
    $> cd data-or
    $> cabal install
    
    -- Without cabal-install, but with the source already:
    $> cd data-or
    $> runhaskell Setup.hs configure --user
    $> runhaskell Setup.hs build
    $> runhaskell Setup.hs test
    $> runhaskell Setup.hs haddock --hyperlink-source
    $> runhaskell Setup.hs copy
    $> runhaskell Setup.hs register

The test step is optional and currently does nothing. The Haddock
step is also optional.


## Portability

An attempt has been made to keep this library as portable as possible.
It is Haskell98 except for the use of CPP, which allows some functions
to be good producers for list fusion in GHC.


## Links

* [Website](http://wrengr.org/)
* [Blog](http://winterkoninkje.dreamwidth.org/)
* [Twitter](https://twitter.com/wrengr)
* [Hackage](http://hackage.haskell.org/package/data-or)
* [GitHub](https://github.com/wrengr/data-or)

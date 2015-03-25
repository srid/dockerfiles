FROM haskell
RUN cabal update
cabal install cabal-install
cabal install -j elm-compiler-0.14.1 elm-package-0.4 elm-make-0.1.1
cabal install -j elm-repl-0.4 elm-reactor-0.3

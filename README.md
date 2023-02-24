# VOIDSPACE

Yo dawg; I heard you like types, so I made a well-typed typing tutor where you can type your types... in SPACE!

[![asciicast](https://asciinema.org/a/212931.svg)](https://asciinema.org/a/212931)

Fight off scary category-theory in outer-space with nothing but your trusty keyboard :)

See how many kills you can get before you asphyxiate in the cold dark void
(trust me, you'll lose eventually :wink: )

## Usage

-   Clone the repo
-   `$ stack install`
-   `$ void-space-exe` (from the root of the repo)
-   Customize `word-list.txt` or add your own space-ships and art in `./art`!
-   Customize values in `src/Config.hs` to tweak difficulty!

## Features

-   [x] Super-awesome recharging shield tech to make the Space Federation proud.
-   [x] Customizable art!
-   [x] Auto-scaling (and customizable) difficulty
-   [x] Super cool space background to impress all your friends (my mother was VERY impressed)
-   [ ] Distributed Client/Server architecture for LAN play! Cuz you gotta have LAN
        parties, how else am I supposed to get rid of all of these Doritos?
-   [ ] Chaotic events!
-   [ ] Powerups!
-   [ ] Co-operative mode!

## Design Principles

Unlike many fun games designed to help you learn Haskell, this one was
intentionally designed to use as many complex and confusing concepts as
possible! The real world's tough kid, best get used to it :wink:, in reality
it's not that bad, but it does use Classy Lenses and some pretty complex
traversals and folds as well as some darker corners of the lens library. Have
fun digging through it! It originally used vectors with dependent types,
representable functors, and the
[`selections`](http://hackage.haskell.org/package/selections) lib, but I
decided to take it easy (for now).


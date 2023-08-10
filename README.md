# Urbit Wordlists

This project contains pre-computed wordlists which can be used for:
- Finding Urbit IDs with interesting names
- Finding planet IDs with interesting sigils

## Layout

This project has the following layout:
```
name/                  Wordlists of English words and approximately-English words that can be made using Urbit phonemes
  approx-double.txt    Phoneme pairs forming two approximately-English words (e.g. bacfed, dispen, datrum, etc.)
  approx-single.txt    Phoneme pairs forming one approximately-English word (e.g. littel, sampel, bacfyr, etc.)
  english-double.txt   Phoneme pairs forming two English words (e.g. barwet, postem, winbet, etc.)
  english-single.txt   Phoneme pairs forming one English word (e.g. barrel, ladder, master, etc.)
  scrabble.txt         Phoneme pairs forming six-letter long words that would be accepted in a game of Scrabble (e.g. darnex, nardus, tasser, etc.)
sigil/                 Wordlists of planets with noteworthy sigils
  any/                 Each file within this directory contains all planets with sigils of a particular form
    chesire.txt        Sigils forming a Chesire Cat grin
    circle.txt         Sigils forming a circle
    flower.txt         Sigils forming a flower
    hills.txt          Sigils where each quadrant has a pill-top shape (the rarest sigil shape repetition)
    orbs.txt           Sigils where each quadrant has a circle shape
    pills.txt          Sigils forming two stacked, horizontal pills
    square.txt         Sigils forming a square
    star-circle.txt    Sigils forming a star shape out of negative space (circular positive space)
    star-square.txt    Sigils forming a star shape out of negative space (square positive space)
  lines/               Each file within this directory contains all planets with sigils of a particular form that have matching lines
    circle.txt         Sigils forming a circle with matching lines
    pills.txt          Sigils forming two stacked, horizontal pills with matching lines
    pizza.txt          Sigils which look like a sliced pizza
    square.txt         Sigils forming a square with matching lines
```

## Sigil Examples

Below are links to example sigils demonstrating each of the shapes described above:
- [Chesire Cat Grin](https://network.urbit.org/~ralbel-ridnym)
- [Circle](https://network.urbit.org/~bonbec-doslux)
- [Circle (matching lines)](https://network.urbit.org/~bonpyl-natryg)
- [Flower](https://network.urbit.org/~bitmyr-hallyd)
- [Hills](https://network.urbit.org/~tobtun-nimfun)
- [Orbs](https://network.urbit.org/~barbet-boldul)
- [Pills](https://network.urbit.org/~bilber-bordev)
- [Pills (matching lines)](https://network.urbit.org/~bordun-sorlex)
- [Pizza](https://network.urbit.org/~rablus-tacryp)
- [Square](https://network.urbit.org/~binben-dinsut)
- [Square (matching lines)](https://network.urbit.org/~hinneb-pinmeb)
- [Star (circle)](https://network.urbit.org/~doctyd-litdel)
- [Star (square)](https://network.urbit.org/~fadryl-micrep)

## Recommended Usage

Include this project as a [git submodule](https://github.blog/2016-02-01-working-with-submodules/) in your own project and do cool stuff.


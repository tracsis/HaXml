## 1.25.12 (2022-10-18)
- Allow parsing empty strings, avoiding space leak #13 (Teo Camarasu)

## 1.25.11 (2022-09-13)
- revert "allow empty text content #10" to avoid haxr memory leak

## 1.25.10 (2022-09-12)
- better pretty printer formatting #8 (Alexander Vieth)
- allow building with GHC 9.4 #9 (Andreas Abel)
- allow empty text content #10 (Teo Camarasu)

## 1.25.9 (2022-04-10)
- fix 1.25.7 regression in Xtract.Parse (#7 by Isaac van Bakel)
- comment typo fixes (#6 by Eric Lindblad)
- include README file

## 1.25.8 (2021-11-22)
- version the License tag in HaXml.cabal as LGPL-2.1 (#3)
- allow building with ghc 9.2 (#4)

## 1.25.7 (2021-10-15)
- many hlint fixes
- fix the rendering of time durations (#1)

## 1.25.6 (2021-09-26)

- GHC 8.8, 8.10, and 9.0 compatibility

## 1.25.5 (2018-10-30)

- GHC-8.4 and GHC-8.6 compatibility
  - Monoids have Semigroup instances

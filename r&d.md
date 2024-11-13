## [ ] Name -> jiva?

  * jzu
  * jezu
  * jizy
  * jizy
  * jacy
  * jaiva
  * jaiv
  * jiva
    * jivascript
    * j-iva (nov)
    * jiva from sanscrit
  * jaga
  * jim
    + dim
    - taken
  * subji
    + sub-ji
  * sruti
  * jasm?
    + wasm + js
  * wasc
    + wasm compiler
    + wasm script
  * floatscript
  * numscript
  * bytescript

## [ ] Applications?

  * Web-audio-api?
  * Floatbeats?
  * Metronome?
  * Player?
  * Srutibox

## [ ] Arrays: GC vs memory

  0. GC

## [ ] Closures: how?

  0. Set of vars
    - overhead per-function call

  1. Struct create per fn call
    - relative overhead of setting current struct
    ? is there a way to set array only if it's changed?

  1.1 `if (curStruct != newStruct) { prevStruct = curStruct; curStruct = newStruct; } ... if (prevStruct) curStruct = prevStruct`
    + only 2 condition checks overhead
    + can be handled on polyfill level

## [ ]
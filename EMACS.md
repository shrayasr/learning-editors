# learning-emacs
> My entry into the emacs church

## Points of interest

* `ctrl L` moves the cursor line to the middle of the screen, again moves it to the top and again to the bottom.
* `CTRL` characters are used to talk about the smallest block of operation (chars, lines, etc). The same keybindings used with `META` talk to blocks defined by the smaller `CTRL` based blocks. Eg: `ctrl a` moves to start of line, where `meta a` moves to the start of a sentence.
* Defaults are much more palitable
* Nice differences between killing and deleting text and how emacs understands when to do what
* Very context understanding. Nice how it remembers that successive `ctrl k`s is the same block and yanks all of them together
* Major modes are definitely interesting. I like now the apostrope is considered as a word seperator in **fundemental** mode but considered as part of the word (like it should be) in **text-mode**
* Incremental search is super! Love the way the highlighting works AND the way `<DEL>` is handled.

## Botherations

* Too much effort to type numeric arguments to commands `ctrl u 10 ctrl v`
* Easier way to navigate the yank ring?
* Documentation around `C-M-V` isn't really clear. Control Meta characters should have been introduced before being put to use


## Questions

* What does the `a` in `ctrl a` mean? 
* Why suddenly to use `ctrl w` to delete a region? 

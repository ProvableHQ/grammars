# Grammars

This repository collects grammar specifications
for languages and formats in the Aleo ecosystem.
Copies of these grammars can be found in other Aleo repositories,
where they are used for various purposes (e.g. documentation),
but the main copies are in this repository.
These main copies should be the first ones to be edited
for changes and extensions,
with the other copies to follow suit as practical
(updating the other copies may require
updating other parts of those repositories,
so it is expected that those copies may be temporarily out of date
when these main copies are modified).

Contents of this repository:
- `leo.abnf` is the ABNF grammar of Leo.
- `aleo.abnf` is the ABNF grammar of Aleo instructions.

See the [Aleo developer documentation](https://docs.leo-lang.org/getting_started)
for infomation on Leo and Aleo instructions.

See
[this Wikipedia page](https://en.wikipedia.org/wiki/Augmented_Backus–Naur_form)
for information on the ABNF grammar notation.
Note that lines of ABNF grammar files must be terminated by CR LF,
which is enforced via `.gitattributes` file entries;
this is a requirement of the ABNF grammar notation itself
(but does not apply to languages whose syntax is specified in ABNF).

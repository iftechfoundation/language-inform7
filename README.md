# language-inform7 package

Inform 7 language grammar for Atom
- Created by Andrew Plotkin <erkyrath@eblong.com>
- https://github.com/erkyrath/language-inform7
- https://atom.io/packages/language-inform7

This started as a fork of [Robert Clarke's Inform grammar][kumo]. It's turned into a total rewrite, however. I've renamed it to include the "7" (since Inform 6 is a different language) and added "7" to all the syntax classes.

[kumo]: https://github.com/kumo/language-inform

This correctly colors:

- Strings with bracketed substitutions
- Nested comments
- Section header lines
- Inform 6 inclusions
- The documentation section at the end of an extension

I do not try to color all of Inform 6 syntax. (There's a standard algorithm for this, but it's not regexp-based and I never liked it anyhow.) I just color I6 strings, dict words, and comments within I6 inclusions.

Known bugs:
- I7 requires section headers to be set off by blank lines above and below. This grammar does not check that requirement.

Screenshot:

![Screenshot](https://cloud.githubusercontent.com/assets/65666/12072581/bf622752-b0b3-11e5-98b4-19dd0179fac4.png)

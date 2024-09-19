# pgm.h

STB-style single-header library for reading, editing and writing PGM images.

Written in strict ("pedantic") ANSI C for maximum portability.

Does allocate (sorry! But it's very easy to just change the malloc calls to your
own. In fact, it's very easy to make it don't depend on LibC at all).

## License

This is public domain software, but you can choose to use it under MIT if you
want.

## History

I wrote a library for handling PGMs to use in a very interesting college
assignment where we had to use convolution to compare images of some trees. As
this may be useful, I ported it to a single-header.

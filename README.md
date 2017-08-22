# The `octave` Package for Typesetting Musical Pitches with Octave Designations

The `octave` package typesets musical pitch names with designations for the
octave in either the Helmholtz system (letter name with subscript numeral for
the octave, where middle C is `C4`), or the traditional system with upper- and
lowercase letters and prime symbols, where middle C is `c'`.

Using this package, authors can just write `\pitch{C}{4}` and then by calling a
package option (`number` or `prime`), can render all the pitch names in either
system.  
The system can also be changed mid-document.

This material is subject to the current version of the LaTeX Project Public License.
The author and maintainer is Andrew A. Cashner, `andrewacashner@gmail.com`.

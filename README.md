`duckuments`: minimal working duckuments
========================================

This package may be distributed and/or modified under the conditions of the
LaTeX Project Public License (LPPL), either version 1.3c of this license or (at
your option) any later version.  The latest version of this license is in the
file

   https://www.latex-project.org/lppl.txt

Copyright (C) 2018 by Jonathan P. Spratte

This package provides means to create duckified dummy contents. The following
macros are available:

 - `\duckument[key=val]` - print a short duckument
 - `\blindduck[key=val]` - print a paragraph
 - `\ducklist(*){environment}` - create a list of type `environment`
 - `\ducklistlist(*){environment}` - create nested lists
 - `\duckitemize` - `\ducklist{itemize}`
 - `\duckenumerate` - `\ducklist{enumerate}`
 - `\duckdescription` - `\ducklist{description}`
 - `\duckumentsCreateExampleFile`
 - `\duckumentsDrawRandomDucks`

It also provides `example-image-duck.pdf` which contains several pages of random
`tikzduck`s. Also `\includegraphics` is patched so one can use
`\includegraphics{example-image-duck}` to in fact use a random duck out of
`example-image-duck.pdf`. The behaviour of `\includegraphics` shouldn't be
altered for other files.

At the moment, the package only works with pdfTeX and LuaTeX.

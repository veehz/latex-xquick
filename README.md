# The `xquick` package

The `xquick` package is used to create notes (in the form **I** like) in the `elsarticle` class.


## Commands

 - *maketitle*: A redefined *maketitle*
 - *xtitle*: An unnumbered title (will not be included in the table of contents)
 - *resetcount*: Reset counter for *section* (i.e. \setcounter{section}{0})
 - *xcopyright*: Set the copyright part (left footer). (Original: Copyright \the\year \theauthor)
 - *zhdoc*: Turns document into Chinese document
 - *setversion*: Sets version
 - *rmtwocolumn*: Remove *twocolumn*


## Elements

 - *thetitle, thedate, theauthor*: Shows the title, the date and the author respectively
 - *xdate*: Shows today's date in form *yyyymmdd*
 - *versionx*: Shows version


## Functions

 - *twocolumn* automatically activated
 - Redefined *maketitle*
 - Table of contents is hyperlinked
 - Removed vertical spacing in lists
 - Removed dots in table of contents
 - Set margin to 1 inch
 - Set paper to A4 Paper
 - Header/footer is set using the package *fancyhdr*


## Other Packages Included

 - `{hyperref}`
 - `{enumitem}`
 - `[titles]{tocloft}`
 - `{fancyhdr}`
 - `{titling}`
 - `{CJK}`
 - `{CJKnumb}`

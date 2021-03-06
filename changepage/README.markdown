
The CHANGEPAGE and CHNGPAGE packages
================

Provides commands to change the page layout in the middle of a document,
and to robustly check for typesetting on odd or even pages.

The changepage package is an extraction of code from the memoir class.
It is a functionally-equivalent replacement for chngpage package.
Because chngpage is not compatible with memoir, its use is now deprecated.


CHANGE HISTORIES
---------------

### CHANGEPAGE

version 1.0c (2009/10/20)

- Real PDF documentation

version 1.0b (2009/09/02)

- New maintainer (Will Robertson, funnily enough)

version 1.0a (2008/08/15)

- Fixed typo (a missing `p', courtesy Will Robertson)

version 1.0 (2008/03/22)

- First public release

### CHNGPAGE

version 1.2b (2009/10/20)

- Real PDF documentation

version 1.2a (2009/09/02)

- New maintainer (Will Robertson)

version 1.2 (2003/08/10)

- Fixed \checkoddpage to handle page numbers other than arabic
- Eliminated special \checkoddpage code for hyperref

version 1.1c (2001/02/24)

- Fixed problem when used with the calc package
  (can't do \setcounter{cp@tempcnt}{\cp@pageref{....}}
- Fixed problem when used with the hyperef package
  (hyperref adds new arguments to \newlabel in the *.aux file)

version 1.1b (2001/01/31)

- Added strict option for robust adjustwidth; checks odd/even
  pages via labels instead of by the page counter.

version 1.1a (2001/01/18)

- Added missing {} in last 4 arguments of \changepage

version 1.1 (2000/07/22)

- Empty arguments made available
- Added adjustwidth environment


INSTALLATION
---------------

Run `latex` on changepage.tex to produce the files
  changepage.ins, changepage.sty, and chngpage.sty,
as well as to compile the PDF documentation.

Execute `latex changepage.ins` to produce the files above
except changepage.ins itself (and the PDF file, obviously).


COPYRIGHT AND LICENSING
---------------

Author: Peter Wilson (Herries Press)  
Maintainer: Will Robertson (will dot robertson at latex-project dot org)  
Copyright 2000–2008 Peter R. Wilson  
Copyright 2009 Will Robertson

This work may be distributed and/or modified under the
conditions of the LaTeX Project Public License, either
version 1.3c of this license or (at your option) any
later version: <http://www.latex-project.org/lppl.txt>

This work has the LPPL maintenance status "maintained".
The Current Maintainer of this work is Will Robertson.

This work consists of the files changepage.tex and the
derived files changepage.sty, chngpage.sty, changepage.ins.


MAINTENANCE
---------------

Please report bugs or request features:  
  <http://github.com/wspr/herries-press/issues>

Developmental and historical versions:  
  <http://github.com/wspr/herries-press>

Current release versions:  
  <http://ctan.tug.org/pkg/changepage>  
  <http://ctan.tug.org/pkg/chngpage>


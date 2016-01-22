# License

nihbiosketch.cls 
Copyright 2016 Paul M. Magwene

This work may be distributed and/or modified under the
conditions of the LaTeX Project Public License, either version 1.3
of this license or (at your option) any later version.

The latest version of this license is in

  http://www.latex-project.org/lppl.txt

and version 1.3c or later is part of all distributions of LaTeX
version 008/05/04 or later.

This work has the LPPL maintenance status `maintained'.

The Current Maintainer of this work is Paul M. Magwene

This work consists of the files nihbiosketch.cls, nihbiosketch.cls


# latex-nihbiosketch

A LaTeX class implementing the new (as of 2015) NIH Biographical Sketch Format.

This LaTeX document class tries to adhere to the Biographical Sketch formatting requirements outlined in NIH Notice [NOT-OD-15-032](http://grants.nih.gov/grants/guide/notice-files/NOT-OD-15-032.html).  This new format is required for applications submitted for due dates on or after May 25, 2015.

I tried to mimic the example documents provided on the [SF 424 (R&R) Forms and Applications page](http://grants.nih.gov/grants/funding/424/index.htm#format) as closely as possible. I have used this class for my own  grant submissions; however I offer no guarantee of conformity to NIH requirements.

To use:

 1. Add the file `newbiosketch.cls` to your local `texmf` tree
 2. Pattern your document based on `example-nihbiosketch.tex` 
 3. Compile your document with `xelatex` or `lualatex` (required for the Arial font that NIH favors)



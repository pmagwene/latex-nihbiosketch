# latex-nihbiosketch

A LaTeX class implementing the new (as of 2015) NIH Biographical Sketch Format.

This LaTeX document class tries to adhere to the Biographical Sketch formatting requirements outlined in NIH Notice [NOT-OD-15-032](http://grants.nih.gov/grants/guide/notice-files/NOT-OD-15-032.html).  This new format is required for applications submitted for due dates on or after May 25, 2015.

I tried to mimic the example documents provided on the [SF 424 (R&R) Forms and Applications page](http://grants.nih.gov/grants/funding/424/index.htm#format) as closely as possible. I have used this class for my own  grant submissions; however I offer no guarantee of conformity to NIH requirements.

To use:

 1. Add the file `newbiosketch.cls` to your local `texmf` tree
 2. Pattern your document based on `example-nihbiosketch.tex` 
 3. Compile your document with `xelatex` or `lualatex` (required for the Arial font that NIH favors)



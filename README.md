# latex-nihbiosketch

A LaTeX class implementing the new NIH Biographical Sketch Format.

This LaTeX document class tries to adhere to the Biographical Sketch formatting requirements outlined in NIH Notice [NOT-OD-15-032](http://grants.nih.gov/grants/guide/notice-files/NOT-OD-15-032.html).  This new format is required for applications submitted for due dates on or after May 25, 2015.

I tried to mimic the example documents provided on the [SF 424 (R&R) Forms and Applications page](http://grants.nih.gov/grants/funding/424/index.htm#format) as closely as possible. I have used this class for my own grant submissions; however I offer no guarantee of conformity to NIH requirements.

## Quick Start

To use:

 1. Add the file `newbiosketch.cls` to your local `texmf` tree
 2. Pattern your document based on `example-nihbiosketch.tex` 
 3. Compile your document with `xelatex` or `lualatex` (required for the Arial font that NIH favors)
 
 
## Details
 
The `nihbiosketch` class is based off of the standard article class.  It defines several new commands and environments to make creation of an NIH Biosketch relatively straightforward. The most straightforward approach is to use the `example-nihbiosketch.tex` document as a template for your biosketch.
 
### New commands
 
 * `\name` -- your full name (lastname, firstname)
 * `\eracommons` -- your ERA Commons user name
 * `\position` -- your position / job title
 * `\grantinfo{Grant #}{Grant PI}{Grant Dates}{Grant title}{Grant description}{Your role}` -- takes care of formatting grant info in standard NIH format
 
 
### New environments
 
 * `\begin{education}...\end{education}` -- A table environment for listing academic degrees and training. The four fields of this table are: 1) Institution and Location; 2) Degree; 3) Completion date; 4) Field of study.
 
 * `\begin{statement}...\end{statement}` -- This environment temporarily changes paragraph indent in a manner appropriate for the personal statement section. Wrap your personal statement (and up to four peer reviewed publications that specifically highlight your experience and qualifications for the proposed project) in this environment.
 
 * `\begin{datetbl}...\end{datetbl}` -- A table environment that makes neatly aligned information with accompanying dates. Use this for employment, honors, other positions, awards, etc. This is a two column table, where the first column is for date information, and the second column is for descriptive text (second column wraps lines).

 
## Availability

The canonical source repository for this package is https://github.com/pmagwene/latex-nihbiosketch.

This package is also available via CTAN at http://www.ctan.org/pkg/nihbiosketch and hence via your standard LaTeX package manager if you use TeX Live (e.g. TeX Live Utility).


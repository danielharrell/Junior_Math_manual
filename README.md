# Junior_Math_manual
 The current Junior Math manual used at St. John's College, Annapolis

## Edits ### For 2022 manual
- Commented out `pdfcprot` (line 37); deprecated package.	
- Corrected a number of errors from the list in Greg Recco's 2021 archon report.
- Followed a suggestion of the 2021 report to replace a figure from the "Hanging Chain" paper (no longer read) with a figure from the "New Method" paper (Figure 1) for the cover of the manual. Also rotated the image of the "New Method" figure and put it in `fig` folder (`Figure2B.png`)
- Deleted spaces on either side of em-dashes ("---") from several Leibniz papers to improve typesetting.
- Created more space between equation and footnote line, page 22.
- Moved code for figure 39 down a paragraph to put figure on page with text.
- Added `Alternate_text` and `figs_unused` folders. Put relevant files in those folders.
- Replaced hand-drawn figure for first finding-tangent example (fig.~28, p.~72) with a TikZ picture.
- Replaced 'and' with semicolon to reformat lines on pages 123 and 124.
- Added page reference to Figure 16 (on p. 127; figure on p. 129).
- Deleted repitition of Figure 15 (pp. 128-30).
- Made all "QEDs" consistent in format (`\textsc{q.e.d.}`)
- Reduced space between items in enumerated lists.
- Reduced spacing between integral sign and terms in online integral expressions.
- Put in spacing where lacking in certain places.
- Enlarged parentheses in display size expressions and equations.  
## To Do
- See if notes can be separated from text to produce separate manuals for readings and commentary.
- See if `\documentclass` of manual can be changed to `memoir`.
- Replace handdrawn figures for $v=x^2+2$ (figs 20 and 24) with TikZ pictures.
- Find other formatting issues to improve.
- Replace `$$` with `\[`,`\]` in LaTeX code.
- Find other outdated code to update or comment out.
- Replace Figure 1 in Set Theory text with TikZ picture.

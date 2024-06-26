# Junior_Math_manual
 The current Junior Math manual used at St. John's College, Annapolis

## Edits
### For 2024 manual
- 2023 manual never printed; for 2024 only change is to year on cover page.
### For 2023 manual
#### Typesetting
- Corrected a number of punctuation and formatting errors from the 2022 manual.
#### Content
- Rewrote parenthetical paragraph in appendix on transcendence of circle's quadratrix to correct error and clarify how line AMC is a cosine curve. 
- Deleted paragraph in set theory text on hyperreal numbers. (The cardinality given for those numbers was incorrect.)
- Added simpler proof in footnote for similarity of triangles in Note 13 of Leibniz "Recondite" paper.
- Replaced figure in proof for first fundamental theorem.
#### Code
- Updated code for greek font to `\foreignlanguage` from `\selectlanguage`.

### For 2022 manual
<details>
 <summary>Click to read</summary>
 
#### Typesetting
- Corrected a number of errors from the list in 2021 archon report.
- Followed a suggestion of the 2021 report to replace a figure from the "Hanging Chain" paper (no longer read) with a figure from the "New Method" paper (Figure 1) for the cover of the manual. Also rotated the image of the "New Method" figure and put it in `fig` folder (`Figure2B.png`)
- Replaced hand-drawn figure for first finding-tangent example (fig.~28, p.~72) with a TikZ picture.
- Reformatted Table of Contents for better typesetting.
- Deleted spaces on either side of em-dashes ("---") from several Leibniz papers to improve typesetting.
- Created more space between equation and footnote line, page 22.
- Moved code for figure 39 down a paragraph to put figure on page with text.
- Replaced 'and' with semicolon to reformat lines on pages 123 and 124.
- Added page reference to Figure 16 (on p. 127; figure on p. 129).
- Deleted repitition of Figure 15 (pp. 128-30).
- Made all "QEDs" consistent in format (`\textsc{q.e.d.}`)
- Reduced space between items in enumerated lists.
- Reduced spacing between integral sign and terms in inline integral expressions.
- Put in spacing where lacking in certain places.
- Enlarged parentheses in display size expressions and equations.  
#### Code
- Commented out `pdfcprot` (line 37); deprecated package.
#### Files	
- Added `Alternate_text` and `figs_unused` folders. Put relevant files in those folders.
</details>

## To Do
<details>
 <summary>Click to read</summary>
 
### Errors to correct
- [X] Page 216, line 10: replace a with alpha.
- [X] Delete hyperreals reference in set theory text.
### Typesetting
- [ ] Separate notes from text to produce separate manuals for readings and commentary.
- [ ] Replace handdrawn figures for $v=x^2+2$ (figs 20 and 24) with TikZ pictures.
- [ ] Find other formatting issues to improve.
- [ ] Replace Figure 1 in Set Theory text with TikZ picture.
- [ ] Reformat Table of Contents to look nicer, along with section headings and the like.
- [ ] Correct cross-references (to Dedekind, etc.) in Cantor text.
### Code
- [ ] Change `\documentclass` of manual from `article` to `memoir`; make other changes as needed.
- [ ] Replace `$$` with `\[`,`\]` in LaTeX code.
- [ ] Find other outdated code to update or comment out.
- [ ] Replace `{center}` environment in figures with `\centering` command
</details>

 
  # asmeconf: A template for ASME conference papers #
 
  ### Overview ###
  This class provides a template to format ASME Conference papers according to
  the requirements on ASME's web pages (as posted in 2020).
  
  [www.asme.org/publications-submissions/proceedings/formatting-the-paper](https://www.asme.org/publications-submissions/proceedings/formatting-the-paper)
  
  The asmeconf class provides access to many features not available in older LaTeX templates for ASME papers. It is designed to approach the following aims:

- match ASME's font current specifications and layout

- match ASME's current reference formats, and add support for DOI and URL fields

- support hyperlinks to figures, tables, equations, references, and external URLs

- support pdf bookmarks and metadata

- set author names and addresses in either the traditional grid or the more recent inline style

- enable various math and text features with newtxmath and newtxtext packages

- support bold face, sans serif math in section headings

- support footnotes in section headings

- provide line numbers for editing and review

- support balancing of columns on last page

- support PDF/A (archival) standards if desired

- support copyright footer for federal employees and contractors

  The .tex and .cls files are commented and should be self-explanatory.

  The files in this distribution are:

          README.md              --  this file
          asmeconf.cls           --  the class file
          asmeconf.bst           --  bibtex style for ASME conference format
          asmeconf-template.tex  --  a latex template/example for this class
          asmeconf-template.pdf  --  documentation/sample paper
          asmeconf-sample.bib    --  a sample bibliography file
          *
          sample-figure-1.pdf, 
          sample-figure-2a.pdf, 
          sample-figure-2b.pdf   -- figures for the example
          *
          author-grid-style.pdf  -- example of title page with "authorgrid" option

  This work is not a publication of ASME itself. 
  
  #### Author ####
  
  John H. Lienhard V
  
  Department of Mechanical Engineering
          
  Massachusetts Institute of Technology
          
  Cambridge, MA 02139-4307 USA


 ---
 
 #### Change log ####

 v1.22 (2020/12/25): Enable language-specific fonts for Greek, Vietnamese, and cyrillic-alphabet languages, with examples of abtracts in these languages; revise handling of class options and keys; edit documentation.

 v1.21 (2020/12/10): Edit documentation; update some usage of xparse under the hood; confirm compliance with substitutefont package. 
 
 v1.20 (2020/11/08): Add options to change copyright notice for federal employees and contractors; rename option "oldauthors" as "authorgrid"; other minor edits. Thanks to Bret Van Poppel for suggesting the federal copyright.
 
 v1.19 (2020/08/12): Add support for PDF/A archival standards (1b, 2b, 2u, 3b, 3u), as the newtx fonts have recently gained complete unicode maps; set pdf to load with single-page display rather than 2-page spread; add example of grid-style author block.
 
 v1.18 (2020/04/14): edit and expand documentation; revise sample .bib file; extensive edits to asmeconf.bst, to better support hyperlinks, to correct eid error, and for better conformance to ASME style (details listed in .bst file); add foreign language example.
 
 v1.17: set T1 font encoding with utf-8 input, ensure LuaLaTeX compatibility; load hologo and metalogo packages; edit documentation.
 
 v1.16: remove xpatch and comment packages from class file; disable \\( and \\) in pdf bookmarks to avoid warnings; edit documentation.
 
 v1.15: correct extra space left by \\CorrespondingAuthor when that author is not last; correct breakage of \\ref in captions.  Thanks to Bret Van Poppel for reporting these issues.
 
 v1.14: edit documentation; use 2020 IMECE header in layout example
 
 v1.13: add babel options for language support; minor text edits; adjust nomenclature list penalties
 
 v1.12: add support for line numbers for editing; add support for final column balancing; edit skips in nomenclature; adjust \\tolerance and \\emergencystretch (for line breaking); improve support for equation tags in captions; adopt standard \\maketitle and \\title commands; include \\versionfootnote for tracking revisions of draft.
  
 v1.11: minor adjustments to title, author, and affiliation layout
 
 v1.1:  revise several parts of the layout to match ASME's updated specifications from Summer 2019 (including author block, abstract font, placement of nomenclature, and minor spacings); add .bst support for online references and eprints; expand documentation significantly; guidance on fitting equations into columns. 
 
 v1.07: improve support for numbered section headings; allow omission of corresponding author email; edit documentation
 
 v1.06: automate bold sans math in captions and headings; small adjustments to default spacings; adjust font of paper number to 18 pt; edit documentation
 
 v1.05: minor code clean-up; change to keyvalue for to control font for superiors
 
 v1.04: fix option passing for mathalfa package; adjust \\entry to create nomenclature subheadings efficiently.

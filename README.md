 
  # asmeconf: A LaTeX template for ASME conference papers #
 
  ## Reporting Issues ##
  This GitHub site is for reporting issues (bugs, feature requests) for the asmeconf LaTeX template.
  
  For general questions about LaTeX (or Tex Live, Overleaf, etc.), [tex-stackexchange](https://tex.stackexchange.com/) is an excellent source of advice.
  
  ## Downloading the code ##
   The asmeconf files may be downloaded from CTAN: [ctan.org/pkg/asmeconf](https://ctan.org/pkg/asmeconf). 
   
   This class is also included in standard distributions such as TeX Live, MikTeX, and Overleaf. 
  
  ## Overview ##
  This LaTeX class and BibTeX style provide a template to format ASME Conference papers according to
  the current requirements on ASME's web pages: [www.asme.org/publications-submissions/proceedings/formatting-the-paper](https://www.asme.org/publications-submissions/proceedings/formatting-the-paper)
  
The asmeconf class provides access to many features not available in older LaTeX templates for ASME papers. It is designed to approach the following aims:

- match ASME's font current specifications and layout

- match ASME's current reference formats, and add support for DOI and URL fields (asmeconf.bst replaces asmems4.bst)

- support hyperlinks to figures, tables, equations, references, and external URLs

- support pdf bookmarks and metadata

- set author names and addresses in either the traditional grid or the more recent inline style

- provide line numbers for editing and review

- support balancing of columns on last page

- support PDF/A (archival) standards if desired

- support copyright footer for federal employees and contractors

- enable various math and text features with newtxmath and newtxtext packages

- support bold face, sans serif math in section headings

- support footnotes in section headings

- enable passages in other languages, e.g., for a translation of the abstract or a quotation

- support for many scripts: Latin, Arabic, Bengali, Chinese, Cyrillic, Devanagari, Greek, Hangul, Japanese, Tamil

  The .tex and .cls files are commented and should be self-explanatory.

  The files in this distribution are:

          README.md              --  this file
          asmeconf.cls           --  the class file
          asmeconf.bst           --  bibtex style for current ASME conference format
          asmeconf-template.tex  --  a latex template/example for this class
          asmeconf-template.pdf  --  documentation/sample paper
          asmeconf-sample.bib    --  a sample bibliography file
          *
          sample-figure-1.pdf, 
          sample-figure-2a.pdf, 
          sample-figure-2b.pdf   -- figures for the sample paper
          *
          examples/              -- a directory of examples: 
                                      -- nonlinear ode integration within LaTeX using Lua code
                                      -- fontspec for abstracts in 25 languages in one paper
                                      -- grid-style layout of author names/addresses
                                      -- footers for government employees
                                      -- asmewide.sty and example of use, for two-column equations

#### Author ####
  
John H. Lienhard V, Department of Mechanical Engineering, MIT, Cambridge, Massachusetts, USA


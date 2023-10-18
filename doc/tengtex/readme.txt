tengtex.tex -- TengTeX for TeX typesetting in Feanorian tengwar
tengtex.sty -- TengTeX for LaTeX typesetting in Feanorian tengwar
-----------------------------------------------------------------
Version 1.10, 22 September 2000
Version 1.01, 22 September 1996
Version 1.00, 22 September 1994

The package contains the following files:

(TeX sources)
readme.txt    This file.
tengtex.tex   TeX style sheet.
tengtex.sty   LaTeX style sheet.
tengdoc.tex   User's manual in LaTeX.
vanda.tex     Pseudo-copyright oath (in English and Quenya).

(MF sources for Computer Modern/Roman Tengwar)
tiad.mf       Family definitions.
tiada.mf      Accents.
tiadd.mf      Digits.
tiadl.mf      Primary letters for Computer Modern Tengwar.
tiadladd.mf   Primary letters for Computer Roman Tengwar.
tiadp.mf      Punctuation.
tiads.mf      Secondary tengwar.
tiadr10.mf    Regular typeface.
tiadssbx10.mf Sans serif boldface extended.
tiadtt10.mf   Typewriter.

(Others)
tengdoc.dvi   User's manual in Device Independent form.
tengdoc.pdf   Ditto in Portable Document Format.
tengdoc.ps    Ditto in PostScript format.

To compile the manual you need to do one of the following things:

* Get the Sauter distribution and then run MetaFont on tiadr10.mf
  and LaTeX on tengdoc.tex
or
* Get Julian Bradfield's teng10.mf or Michael Urban's tengwar.mf,
  run MetaFont on it, uncomment line 19 or 20 of tengdoc.tex and
  then run LaTeX on it.

-----------------------------------------------------------------

Differences between Version 1.10 and Version 1.01:

* Scaling has been added.
* The Computer Modern/Roman Tengwar family has been added.
  Computer Modern Tengwar is now TengTeX's default.
* Some subtle errors in the macro definitions have been corrected.

-----------------------------------------------------------------

Differences between Version 1.01 and Version 1.00:

* The style sheet has been adapted to LaTeX2e.
* Some subtle errors in the macro definitions have been corrected.
* The Quenya text of the pseudo-copyright oath has been reworked
  in accordance with the designer's current idea of the language.

Ivan A Derzhanski   iad@math.bas.bg
Department of Mathematical Linguistics
   Institute for Mathematics and Computer Science
      Bulgarian Academy of Sciences
   8 Acad G Bonchev St, 1113 Sofia, Bulgaria
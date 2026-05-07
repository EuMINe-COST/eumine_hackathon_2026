EuMINe DataBridge Hackathon 2026 — Report Templates
=====================================================

CONTENTS
--------
eumine_hackathon.sty          LaTeX style file (margins, fonts, colours, header)
template_data_integration.tex Data Integration Report template
template_technical.tex        Technical Report template
example_data_integration.pdf  Compiled example (see below)
example_technical.pdf         Compiled example (see below)


REQUIREMENTS
------------
A standard TeX Live 2020+ (or MiKTeX) installation with:
  geometry, amsmath, amssymb, graphicx, booktabs, longtable,
  siunitx, xcolor, enumitem, caption, subcaption, listings,
  fontenc, inputenc, hyperref, fancyhdr, titlesec


COMPILING
---------
Place eumine_hackathon.sty in the same directory as your .tex file, then:

  pdflatex template_data_integration.tex
  pdflatex template_data_integration.tex   # second pass for TOC + refs

  pdflatex template_technical.tex
  pdflatex template_technical.tex

Or use latexmk for automatic re-runs:

  latexmk -pdf template_data_integration.tex
  latexmk -pdf template_technical.tex


SUBMISSION
----------
Submit the compiled PDF alongside your model code and predictions_test.json.
Name your files:

  <team_name>_data_integration.pdf
  <team_name>_technical.pdf

Upload via the Codabench submission portal before the deadline.


LICENSE
-------
Templates are provided under CC BY 4.0.
You are free to modify them for your submission.

EuMINe Network, 2026

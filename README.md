Visual Diagnostics
==================

This optional accessory to Stan generates visual diagnostics of a HMC run.  

To use, run your compiled model with the flag '--diagnostics=<diagnostic_file>' 
and then call './createAllDiagnostics <diagnostic_file>'.

The code requires a recent version of Stan (commit 2c593e4a65a73ef2a71dd79a9c58278cd725d4b8 
or higher) and a local bash environment, as well as gnuplot (http://www.gnuplot.info/)
and pdflatex (http://www.tug.org/applications/pdftex/).  The latter is packaged with most
LaTeX distributions.

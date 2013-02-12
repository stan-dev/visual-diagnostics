Visual Diagnostics
==================

This optional accessory to Stan generates visual diagnostics of a HMC run.  

To use, run your compiled model (with the graphical_diagnostics branch of Stan) with the flag
'--debug' and then call './createAllDiagnostics samples.csv'.

The code requires a local bash environment, as well as gnuplot (http://www.gnuplot.info/)
and pdflatex (http://www.tug.org/applications/pdftex/).  The latter is packaged with most
LaTeX distributions.

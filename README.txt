This is the readme file accompanying the supplemental data for 
"Experimental demonstration of cheap and accurate phase estimation".
The purpose of this supplemental data folder is to allow the reader
to reproduce all results presented therein.

All calculations are performed using python (http://www.python.org/);
most are executed in IPython notebooks (http://ipython.org/).  The following
packages are used (sources listed in parentheses): 
    numpy (http://www.numpy.org/)
    scipy (http://www.scipy.org/)
    matplotlib (http://matplotlib.org/)
    pygsti (http://www.pygsti.info/)

Note that all plots in the paper are made using the commercial software
DataGraph.  Here we reproduce the plots using the open source software
matplotlib.

File descriptions:

RPE_dataset.txt - The experimental RPE dataset.

GST_dataset.txt - The experimental GST dataset.

Data_to_results.ipynb - Generates the full (N=370) RPE and GST estimates,
    along with 95% GST confidence intervals.

RMS_Error_RPE.ipynb - Generates and saves all subsampled
    RPE results.

RMS_Error_GST.ipynb - Generates and saves all subsampled
    GST results.

[The above two files should be executed prior to executing all subsequent
    notebooks, save for Fig2.ipynb.]

Fig2.ipynb - Generates Figure 2.

Figs3_and_S1 - Generates Figure 3 and Supplemental Information Figure 1 (Figure 6 in arXiv version).

Fig4 - Generates Figure 4.

Figs5_and_S2 - Generates Figure 5 and Supplemental Information Figure 2 (Figure 7 in arXiv version).
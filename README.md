
<h1>Supplemetary material for ``Gene selection and classification of microarray data using random forest''</h1>

<br>
<br>

<p>This is the page for the supplementary material for the paper <a
href="http://www.biomedcentral.com/1471-2105/7/3/abstract">``Gene
selection and classification of microarray data using random forest'' </a>
by Ramón Díaz-Uriarte and Sara Alvarez de Andrés, BMC Bioinformatics,
2006, 7:3. <!-- (Download the previous <a href="rfVarSel.pdf">tech. report pdf</a>. -->  This ms. is also in <a href="http://arXiv.org//abs/q-bio.QM/0503025">arXiv</a>.</p>

<!--
<p>You can read the paper as <a href="./rfVarSel/rfVarSel.html">html</a>, but the <a href="rfVarSel.pdf">pdf</a> is nicer and better formated.  This ms. is also in <a href="http://arXiv.org//abs/q-bio.QM/0503025">arXiv</a>.</p>
-->

<p><a href="rfVarSelSuplMat.pdf">The supplementary material main file</a> 
that contains the additional tables, further details on the
simulations,
data sets.
<!-- and alternative methods -->
</p> 


<br>
<br>
<h2>Additional figures</h2>

<p>
Figure <a href="errors.vs.mtry.pdf">errors.vs.mtry.pdf</a>
(a 3.2 MB download) 
shows the OOB error rate plotted against the mtry factor for different ntree
and nodesize.
</p>


<!--
<p>
Figure <a href = "scree.plots.no-signal.pdf">scree.plots.no-signal.pdf</a>
(a 4.1 MB download) 
shows scree plots for simulated data when genes have no signal (all
4000 genes are unrelated to the outcome). For each of the three class
situations (2, 3, 4 classes) we show four simulated data sets. To
allow for easier visulaization, only the 500 most important genes are
shown.
</p>
<p>
Figure <a href = "scree.plots.simul.data.pdf">scree.plots.simul.data.pdf</a>
(a 26 MB download!) 
shows scree plots for simulated data where a subset of genes are
relevant for prediction, as described in \ref{simul-data}. For each
setting of number of trees ntree = (5000, 40000), and each setting of
mtry factor (1, 5, 8, 13), we show the scree plots for each of the 27
scenarios: number of classes (2, 3, 4) * number of independent
dimensions (1, 2, 3) * number of genes per independent dimension (5,
20, 100). The number of genes shown is smaller than 4000 to allow for
easier visualization of the results.
</p>
<p>
Figure <a href = "scree.plots.simul.data.huge.mtry.pdf">scree.plots.simul.data.huge.mtry.pdf</a>
(a 6.4 MB download!) 
shows scree plots for simulated data, where a subset of genes are
relevant for prediction, as described in \ref{simul-data}. These plots
show the effects of using two extremely large values of mtry: mtry
equal to the number of variables, and mtry equal to half the number of
variables. The number of genes shown is smaller than 4000 to allow for
easier visualization of the results. For computational reasons, we
used only ntree = 5000.
</p>




<p>Figure <a
href="scree.plots.real.data.pdf">scree.plots.real.data.pdf</a>
(a 45 MB download!) 
shows scree plots for nine + 1 real microarray data sets, with
different settings of ntree and mtry.
</p>


<p>Figure <a href="real.data.importances.pairs.pdf">real.data.importances.pairs.pdf</a>
(a 94 MB download!) 
shows the relationships between the variable importances at different
mtry values, for a given ntree.
</p>

<p>Figure <a href="real.data.importances.scatter.pdf">real.data.importances.scatter.pdf</a>
(a 21 MB download!) 
shows scatterplots of the variable importances at different ntree for
a given mtry.
</p>

<p>Figure <a href="scree.plots.real.huge.mtry.pdf">scree.plots.real.huge.mtry.pdf</a>
(a 1.1 MB download!) 
shows scree plots using as mtry values the number of columns or half
the number of columns.
</p>

-->
<br>
<h2>Web server</h2>
<p>At <a href="http://genesrf.iib.uam.es">http://genesrf.iib.uam.es</a> you can find a web-based application that uses the functionality of this package, and allows you to peform the described analyses (and additional ones) without downloading or installing anything to your computer.</p>

<br>
<h2>Code</h2>
<p>The package is available from <a
href="https://cran.r-project.org/web/packages/varSelRF/index.html">CRAN</a>
and all of the code from <a
href="https://github.com/rdiaz02/varSelRF">varSelRF's github repo</a>.
<!-- <p>You can download the <a href="../../Software/varSelRF_0.6-2.tar.gz">source package.</a> --></p>



<br>
<h2>Data files</h2>
<p>You can download the microarray data sets used in the paper in three formats: <a href="data.sets.tar.gz">tar.gz</a> (16 MB), <a href="data.sets.tar.bz2">tar.bz2</a> (12 MB) and <a href="data.sets.zip">zip</a> (16 MB).</p>

<p>The complete set of simulated data are available 
<!-- <a href="http://bioinfo.cnio.es/~rdiaz/rf.paper.simulated.data.tar.bz2">here</a> (beware: 230MB!!).</p> -->
<a href="http://genesrf.iib.uam.es/Examples/simulated.data.tar.bz2">here</a> (beware: 230MB!!).</p>


<hr>

<!-- Created: Fri Apr 30 08:50:18 CEST 2004 -->
<!-- hhmts start -->Last modified: 5 January 2006 <!-- hhmts end -->



<hr>

<!-- <p> -->
<!-- <a href="http://validator.w3.org/check?uri=referer"> -->
<!-- <img src="../../valid-xhtml10.png" alt="Valid XHTML 1.0!" height="31" width="88"></a> -->

<!-- <a href="http://www.anybrowser.org/campaign/">  -->
<!-- <img src="../../anybrowser3.gif" alt="Viewable With Any -->
<!-- Browser" height="31" width="88"></a> -->
<!-- </p> -->



</div>


</body></html>














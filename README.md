---


---

<h1 id="adaptive-random-forest-with-resampling-for-imbalanced-data-stream">Adaptive Random Forest with Resampling for Imbalanced data Stream</h1>
<p>Paper by: Luis Eduardo Boiko Ferreira, Heitor Murilo Gomes, Albert Bifet, Luiz S. Oliveira.</p>
<h1 id="how-to-run">How to run?</h1>
<p>Adaptive Random Forest with Resampling is not yet available in MOA. It has to be build. Use this Repo: <a href="https://github.com/kushvarma/moa.git">https://github.com/kushvarma/moa.git</a> and switch to branch arf_re to get the code. These instruction is for Intellij IDEA</p>
<ul>
<li>One you have the code, switch to branch arf_re</li>
<li>Click on Edit Configuration on Top right on window</li>
<li>Click on Plus on left of window, then select Application.</li>
<li>After that fill following details:</li>
</ul>
<p><img src="https://i.ibb.co/r75pQtZ/moa-build.png" alt="Buld MOA"></p>
<ul>
<li>Click OK</li>
<li>Press Play button next to MOA GUI on top RIght of Intellij</li>
<li>It will open MOA GUI application</li>
</ul>
<h2 id="dataset">Dataset</h2>
<p>The data sets are available in the repo. There are two types of dataset, ARFF for MOA and csv to be used for scikit-multiflow. For scikit-multiflow, the dataset need to be cleaned and modified to run the experiment.</p>
<h2 id="scikit-multiflow-with-adaptive-random-forest-with-resampling">scikit-multiflow with Adaptive Random Forest with Resampling</h2>
<p>We are also working on porting ARF_RE to python. The source code is available on <a href="https://github.com/kushvarma/scikit-multiflow.git">https://github.com/kushvarma/scikit-multiflow.git</a> and branch dm_arf.</p>
<h2 id="results">Results</h2>
<p>The current result is available in Result folder. Comparing result from the Paper.<br>
All the test were run on Core i5 8400/ 32GB RAM machine.</p>


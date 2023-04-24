# Anomaly Detection on BankMarketing Dataset
This a solution notebook to an assignment question given in a Data Mining graduate course. Each code block is accompanied by relevant analysis wherever required. </br>
Dataset link: https://github.com/GuansongPang/ADRepository-Anomaly-detection-datasets/blob/main/numerical%20data/DevNet%20datasets/bank-additional-full_normalised.csv </br>
Samples with Class label 1 are treated as anomalous.</br>
Broadly, the following steps have been performed in this solution notebook:
<ul>

<li> Applied different statistical measures and presented them on infograph. </li>
 <ul>
<li> Count plot and classwise categorical plot for categorical attributes  </li>
<li> Histogram plot for continuous attribute</li>
<li > Pie chart depciting class distribution </li>
<li > Correlation Analysis </li>
</ul>
<li>Using KNN as baseline model and training it on the dataset </li>
<li> Dimensionality Reduction using PCA and retraining the model using reduced dimensions </li>
<ul>
<li> Performed accuracy comparison of baseline model with the new model obatined after retaining various levels of variance (60,70, 80,90,99)% </li>

</ul>

  
<li> Clustering using DBSCAN to remove anomalies and retraining the model after removal of anomalies</li> 

<ul>
<li> Performed accuracy comparison of baseline model with model trained after anomalies removal </li>

</ul>


<li> Used a classification model(Decision Tree) to identify anomalies on test set. Followed by retraining the model after anomalies removal.</li>
  
  
<ul>
<li> Performed accuracy comparison of baseline model with model trained after anomalies removal </li>

</ul>

  
 </ul>
These above assumptions and the flow of work is according to the questions asked in assignment.

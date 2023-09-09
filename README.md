# Market-Segmentation-In-Insurance
<div class="sc-emEvRq gZqHzs sc-hGFITe jXToHY"><h3>WHAT IS MARKET SEGMENTATION?</h3>
<p>In marketing, market segmentation is the process of dividing a broad consumer or business market, normally consisting of existing and potential customers, into subgroups of consumers based on some type of shared characteristics.</p>
<h2>Objective :</h2>
<p>This case requires developing a customer segmentation to give recommendations like saving plans, loans, wealth management, etc. on target customer groups based on TENURE.</p>
<h2>Dataset</h2>
<p>The sample Dataset summarizes the usage behavior of about 9000 active credit cardholders during the last 6 months. The file is at a customer level with 18 behavioral variables.<br>
Variables of Dataset<br>
Balance<br>
Balance Frequency<br>
Purchases<br>
One-off Purchases<br>
Installment Purchases<br>
Cash Advance<br>
Purchases Frequency<br>
One-off Purchases Frequency<br>
Purchases Installments Frequency<br>
Cash Advance Frequency<br>
Cash Advance TRX<br>
Purchases TRX<br>
Credit Limit<br>
Payments<br>
Minimum Payments<br>
PRC Full payment<br>
Tenure<br>
Cluster</p>
<p>The sample Dataset summarizes the usage behavior of about 9000 active credit cardholders during the last 6 months. The file is at a customer level with 18 behavioral variables.</p>
<h2>Machine Learning Findings:</h2>
<p>If you'd notice from the .ipynb file, we used Decision Tree to fit our K-Means in the entire dataset and check for accuracy which is 95%. As mentioned in the previous slide, DBSCAN and MeanShift algorithms yielded unsatisfactory results when it came to clustering observations. Therefore, we will exclude them from the comparison, focusing solely on assessing the performance of the K-means and Agglomerative Clustering algorithms. K-MEANS is the best clustering algorithm for this dataset.</p>

<h2>Machine Learning Flaws and Strength:</h2>
<p>Both the K-means and Agglomerative Hierarchical Clustering methods demonstrated efficiency and accuracy in determining the suitable number of clusters. Additionally, they successfully clustered the majority of observations with an accuracy rate exceeding 90%.​</p>

<p>In contrast, DBSCAN and MeanShift algorithms demanded significant time and effort to identify the appropriate number of clusters. This process involved repeatedly adjusting parameters to achieve the desired cluster count. Furthermore, these algorithms produced subpar results in terms of accurately clustering the observations.</p>

<h2>Advanced Steps:</h2>
<p>To improve the clustering process with DBSCAN and MeanShift, we have a couple of options. One approach is to use image data from the scanned images, as both algorithms are well-suited for computer vision applications. Alternatively, we can employ grid search and hyperparameter tuning to find the best parameters for these algorithms. However, it's important to note that tuning parameters, especially for the MeanShift model, can be time-consuming.</p>

<p>For more insights on this dataset, please click <a href='https://github.com/Izuchukwu234/Market-Segmentation-In-Insurance/blob/main/Market%20Segmentation%20Analysis.pdf'>here</a></p>
</div>

# Cryptocurrencies

This project is to provide insight to Accountability Accounting, a prominent investment bank.  The results are to assist in the decision making of offering Cryptocurrency investment portfolio to their customers.  
<br>
Cryptocurrency is a large market with information that can be overwhelming to identify the best model for a successful investment.  This analysis creates a report on cryptocurrencies that are actively trading on the market.  They were grouped in clusters to create a classification report for this new invesment proposal.
<br>
Since the data is so vast and unknown output, unsupervised machine learning models was used to group cryptocurrencies for clustering algorithms.  The visualizations below show the findings of the analysis. 
<br>
<br>
Before the data could be used in any model, the data was preprocessed and standardized to avoid the skewing of the results.  The PCA (Principal Component Analysis) statistical technique was used to reduce the dimensions to 3 components, specifically on the cryptocurrency algorithm and proof of type.  <br>
![crypto_pca](https://user-images.githubusercontent.com/75437852/116322189-82b21880-a789-11eb-8610-f063006a9503.PNG)<br>
<br>
After compiling the principal components, the array was used to create the Elbow curve below.  This graph identifies the data has 4 KMeans clusters.  The clusters will then be initialized and fit into a model.<br>
![bokeh_plot](https://user-images.githubusercontent.com/75437852/116323036-39fb5f00-a78b-11eb-8d19-6c44ba15dc16.png)<br>
<br>
The final 3D graph was created to visualize the 4 KMeans clusters.  Each different class can be identified by the symbol and color and is labeled with the coin name and the algorithm.<br>
By looking at the graph, there is one outlier principal component.  
* Class 1 group is the lowest principal component; the lowest tradable cryptocurrency.
* Class 0 group is the mediocre principal component; an average tradable cryptocurrency.
* Class 3 group is the highest principal component; the higher tradable cryptocurrency. <br>
![3D](https://user-images.githubusercontent.com/75437852/116323544-387e6680-a78c-11eb-82b5-9e9361e87000.PNG)<br>
<br>
A table was also created with the tradable cryptocurrency information.  The table can be sorted and selected based on performance.<br>
![3D](https://user-images.githubusercontent.com/75437852/116326944-b2661e00-a793-11eb-97bf-ab6987f44fcb.PNG)<br>
<br>
Lastly a scatter plot shows the relation between total coins in circulation (Total Coin Supply) versus total coins earned (Total Coins Mined).  In this graph, the coin name is identified by each data point.


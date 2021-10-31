The data set file "Ads Smith.csv" was derived from the Google Analytics at UMD Robert H. Smith Business School master's landing page. 

Special thanks to professor P.K Kannan for providing this amazing data set!

The notebook aims to dig into the searched keywords to examine the pair of keywords with the best performace along with the relative low spending(cost) by segment keywords into different groups using KMeans clustering. 


# First, 
  I demeaned the four evaluating metrics to remove the effect of a panel cross-sectional dependence to make sure they are work well on common structures. 

# Second, 
  I imported KMeans Clustering from scikit-learn. 

The general workflow is as follows:

1. Initialize a new object: a KMeans object in this case
2. Call the fit method on that object using data to estimate the unknowns in the model
3. Extract and interpret the results 

# Third,
  After we added variable names, observation scatterplot, label for each cluster mean, we iterated the process of testing pairs of keywords. 
  
# Fourth,
  We determined the number of clusters by created a **elbow plot of the SSE values**, combining the results in **Occam's razor** we found that K=3 would be the best option. 
  
# Fifth,
  Combining with other factors and external data that may not provided, we concluded the top 5 best performance keywords:

1. +supply +chain +management +masters (MSC)
2. +quantitative +finance +program (MQF)
3. +ms +in +business +analytics (MSBA)
4. [masters in mis] (MSIS)
5. +msis +programs (MSIS)

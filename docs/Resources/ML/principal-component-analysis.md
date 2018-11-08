# Principal Component Analysis

> Today's topic is *_Principal Component Analysis_*, referred to as PCA in the ML community.
> It's actually not a model. Not really. It's more of an advanced data analysis/preparation tool that allows you to take data that contains a LOT of features and is very highly dimensional and boil it down to a few core features.
> In fact, it does this so well that we even call this process * dimensionality reduction*.
> The process of taking data that contains many, many, many dimensions(over 100 features/columns, for instance) and boiling it down to a fewer amount of features
> You may be thinking, how can we do that? Are we allowed to just drop columns from our data? More importantly: _wouldn't we lose some of our data by dropping columns_?
> The core tenet at the heart of PCA is that not all features are created equal. Rather, different features across your dataset represent * stronger * patterns across your data. Think back to our Titanic data: how a factor like being _male/female_ or being _young/old_ may have had more of a factor in whether you survived or not versus _how many siblings you had_.
> We can use PCA to mathematically reduce the number of features/variables/columns into only those that have the * greatest effect on our target label's variance/spread*.
> In other words, if we have a dataset that has 100 features but 95 of them have less than a combined 5 % impact on our dataset's distribution, why even use them? They may be adding unnecessary noise and confusion to our data!

> We can use PCA to find out which are the 5 features that have the best bearing on the patterns we're looking for - PCA will tell us which features to keep and which ones to drop then, so our model runs more effectively.
> I'd explain more, but I'm really goddamn tired and am starting to forget what I've already written - so I'm just gonna share some kickass resources I used last year to really understand this shit.

PCA is *not* used to *just pick features that contain more of a pattern*. PCA actually constructs new features from the best features it finds.


## Resources
[Visual Explanation of Principal Component Analysis, Covariance, SVD](https://www.youtube.com/watch?v=5HNr_j6LmPc)

[Setosa.io](http://setosa.io/ev/principal-component-analysis/) boasts some of the best statistical and data science-related visualizations I've ever seen in my life. Definitely helped me understand what PCA is actually doing: 

[Towards Data Science](https://towardsdatascience.com/a-one-stop-shop-for-principal-component-analysis-5582fb7e0a9c) always has great in-depth explanations on advanced DS concepts:

This [response](https://stats.stackexchange.com/questions/2691/making-sense-of-principal-component-analysis-eigenvectors-eigenvalues) on Stack Exchange is phenomenal. Someone basically pretended to explain PCA to their grandmother and did an _awesome_ job with breaking the explanation down to its principal components (get it?):

Actually, one thing that's super important to mention that I may have deluded earlier: 

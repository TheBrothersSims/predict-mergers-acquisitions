# predict-mergers-acquisitions
### Machine Learning Project - Predicting Mergers and Acquisitions.
	
	The Brothers Sims
	19/05/07

In this project we will attempt to leverage machine learning to predict mergers and acquisitions. This is a pretty lofty goal, and I'm not even sure if we'll get anything worth talking about... But we're going to try it anyway. 

The main thing to consider first is the data. What data can we use? And where can we get it? The next issue that comes up in my mind is that this is both a classifier challenge as well as a forecasting challenge. It'd be great if we can say "we've predicted that these two companies will merge!!" but it won't be much use for us if we don't know WHEN. That could be in, I don't know, ten years sooo... After that then comes questions like what happens to stocks after M&As, who the target is, which stocks to buy out of the M&A, and other more finance-y related topics. We'll save that for if we get some reasonable results. 

With that in mind, we'll start by just trying to create a binary classifier. Out of a manually collected dataset with company data (including whether they have had an M&A or not), what companies will have an M&A?

After potentially solving that, we can tackle the Pandora's box of WHEN it happens.
## TED Talk Analysis
Statistical analysis and topic clustering for TED Talks 

The 'Ted_Talks' python notebook looks at a simple statistical analysis of the different properties of the Ted Talk data, to try and gain insights, similar to what an analytics data scientist would do. 

The 'TED_NLP_Clustering' notebook groups the Ted Talks together using a clustering method to try and understand what topics yeild the greatest number of views, similar to what a research data scientist would try to implement. Also added are lecture notes for the method this tries to mimic.  

## Results

The results of the clustering were much better than expected. I was able to determine what kind of topics had the highest view count for the Ted Talks by clustering the main words in the transcripts of the talks, and extracting the main topics. Determining whether this is correlation or causation requires further investigation. This kind of topic understanding can be used to parse through high volumes of text at a high level and understand how they relate to key north star metrics (in this case, number of views).

**Note:** The transcipts dataset hasn't been added here, as its too large for github. Go to https://www.kaggle.com/rounakbanik/ted-talks to download the full and complete dataset.

## Usage

After getting a working Jupyter notebook environment and downloading the relevant datasets from the link above, simply clone the repository, and run the cells in the notebook.

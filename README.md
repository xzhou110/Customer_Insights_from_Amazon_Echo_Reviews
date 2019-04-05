# Customer Insights from Amazon Echo Reviews

The project is to perform a topic analysis on customer reviews for Amazon Echo. This is to understand major drivers of positive vs. negative customer experience. The end goal is to use the insights to help business enhance self-awareness and make better decisions. The modeling from this project can be applied to any reviews of any product or service to extract insights. 

### Project Design: 
Step 1: Data retrieval and exploration
Step 2: Broke down reviews into positive (>3 rating) and negative sentiment (<3 rating) groups based on ratings 
Step 3: Performed cluster analysis on positive and negative sentiment groups respectively 
Step 4: If limited information obtained from step 3, perform topic modeling to get more in-depth inisghts 

### Tools: 
- Pandas for data manipulation
- Pickle for data storage
- SVD for dimension reduction
- KMeans for cluster analysis
- LDA for Topic analysis
- Word Cloud for visualization
 
### Data: 
- Dataset #1: Amazon Alexa Device Reviews: ~3k reviews 
- Dataset #2: Amazon Echo Reviews: ~7k reviews

### Algorithms:
- Cluster Analysis
- Topic Modeling

### Learning and Recommended Next Steps:
- Leveraged cloud computing for processing large scale data. Worked with AWS and Zeppline and solved technical challenges
- For next steps, explore possibility of combining cluster analysis with topic modeling to produce more insights

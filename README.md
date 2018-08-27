# Extract Insights of Amazon Echo Reviews

The project is to perform a topic analysis on customer reviews for Amazon Echo. This is to understand what major factors drive positive vs. negative experience. The end goal is to use the insights to help business enhance self-awareness and make better decisions. The modeling from this project can be applied to any reviews of any product or service for insight extraction. 

### Project Design: 
Step 1: Clean up datasets and combine two datasets for analysis
Step 2: Break down reviews into positive (>3 rating) and negative sentiment (<3 rating) groups based on ratings 
Step 3: Performed cluster analysis on positive and negative sentiment groups 
Step 4: If limited information extracted from step 3, perform topic modeling on positive and negative sentiment groups 

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
- Learned to use cloud computing for large scale data. Worked with AWS and Zeppline and solved technical challenges
- For next steps, possible to combine cluster analysis with topic modeling to extract more precise information


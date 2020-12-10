## Answering Questions with Data

### Improve Search results

- ML relies on relevant and large enough data source
- Return relevant results
- Tailored to individual preferences
- Intuitively start thinking about what you need to solve the tasks

### Building a Dataset

- Identifying data fit with dataset
- determining use cases (is dataset complete)
- Annotation of dataset

How model performs depends heavily on data you use

- Data Size
- Pattern Detection
- Data Fit / Goodness of Fit 
    - F1 Score, Precision, Recall, Confusion Matrix
- Data Collection
- Data Relevance

## Data Completeness

- What is the problem you are trying to solve and how does it benefit your end users?
- What data will help you solve that problem?
    - Collect data and observe relationships; patterns and similarities among the data
    - Identify potential anomalies or missing data
- Conduct research and get the best data to serve your use case

## Data Annotation

- They explain about Appen Software as a service 
- Platform
- Job Creation Page
    - Common labelling jobs to explore and create

## Figure 8 Platform

- Uploading data
- Designing an annotation job
- Creating test questions
- Monitoring results

- Answer Yes for every parking sign question and image in the Figure 8 Platform

## Test Questions

Once we have our instructions created we can go into Quality. 
Test Questions are created essentially Ground truth Data. This is to understand what they are doing and ensure Accuracy is maintained. If they fall below accuracy threshold, they are removed from the Job. 

- Create Enought Test Questions
- Once you have enough test questions created, you can go ahead and create a Job
- While the job is running you should go back and look at the Test Questions
- See whether contributors are mis-understanding the job
- This is to identify what's going wrong in the job and whether to augment the mening to the job
- To make contrbutors notice the parking sign, we need to do something
- What the contributors miss, your model may also miss

## Auditing Results

- results are downloaded once the job is complete
- audit the results, to identify where mis-understood, go back update
- Unknown or unable to answer job results

## Planning for longevity

- How can you plan for long term success
- Reflect to more relevant definitions
- If you data does not change, ou can use a static model
- Ever-evolving data, dynamic data is used
- Frequently changing data, you may need to change annotation job and update your data to include more relevant definitions


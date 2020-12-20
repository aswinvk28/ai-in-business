## What are Design Cards?

**Design Cards are One Placard of Information that discusses about Activities it needs to do. The interfaces the subject-area or the domain deals with. For example, Data Architecture Management may have about 2-3 activities and Data Development may have about 4 activities for our Concerned Project.**

**Such Design Cards include ML Pipelines, Training Loops, AI Approach**

Let's discuss about Metrics involved in the Design Card: Data Governance.

### 1. Data Governance

![https://github.com/nscalo/ai-in-business/raw/main/Metrics/images/01.DGovernance.PNG](https://github.com/nscalo/ai-in-business/raw/main/Metrics/images/01.DGovernance.PNG)

_We take the AI Approach into perspective where we address the Business Problem first instrad of the data. Let's dive into the data metrics for Data Governance._

DATA METRICS
------------

Let's perform a mapping between Governance Metrics and the Data Elements in the AI Approach. We take a pragmatic approach to finalise the mapping. The metrics from AI and ML domain are considered as well as those in the Data Management standards domain are also taken into consideration.

- **The Data Value** on **Annotation** depends on: Sensitivity and Specificity (Confusion Matrix)
- **The Data Management Cost** on **Annotation** depends on: Steward Representation / Coverage
- **The Achievement of Objectives** on **Annotation** depends on: Net Promoter Score
- **The # Of Decisions Made** on **Annotation** depends on: Level of Automation
- **The Data Value** on **Availability** depends on: KPIs for Productivity
- **The Data Value** on **Security** depends on: Customer Satisfaction Score
- **The Data Value** on **Provenance** depends on: Data Bias
- **The Data Management Cost** on **Provenance** depends on: Data Formats and Transformation

|   Governance Metrics      |   Data Elements  |            Metric               |
|---------------------------|------------------|---------------------------------|
|   Data Value              |   Annotation     |   Specificity and Sensitivity   |
| Data Management Cost      | Coverage         | Steward Representation          |
| Achievement of Objectives | Annotation       | Net Promoter Score              |
| The # Of Decisions Made   | Annotation       | Level of Automation             |
| Data Value                | Availability     | KPIs / Productivity             |
| Data Value                | Security         | Customer Satisfaction           |
| Data Value                | Provenance       | Data Bias                       |
| Data Management Cost      | Provenance       | Data Formats and Transformation |

__Sensitivity and Specificity (Confusion Matrix)__

1. While annotating data, the mistakes and unidentified objects in images, let's say are taken into consideration with True Positive Rate and True Negative Rate. This is termed as Sensitivity and Specificity. 

- True Positives are those that are correctly identified by the algorithm and the ground truth is positive.
- True Negative are those that are correctly identified by the algorithm as negative and the ground truth is negative. 
- False Positives are those that are wrongly identified as positive, so the ground truth is negative. 
- False negatives are those that are wrongly identified as negative, so the ground truth is positive. 

- Sensitivity is also termed as Recall.
- Specificity is also termed as TNR (True Negative Rate) or Selectivity.
- Confusion Matrix consists of TP, FP, TN and FN

__Steward Representation / Coverage__

2. Annotation will cover the entire dataset and is distributed among people and data models that manually arrive at the answers. This incurs a cost to the management aspect as the tools that produce that amount of productivity is managed for automation as well as the headcount for annotating tasks and job management is an additional cost incurred to businesses. 

- Coverage of the dataset is a key characteristic to determine the degree of influence of the dataset with model evaluation and annotation tools. Coverage is a stewardship responsibility too and it lie either at the automated level or the defined level. 
- The greater the coverage of the dataset for our job the better is the model.

__Net Promoter Score__

3. While annotating, the net promoter score is used to achieve the objectives of producing valid answers to the given questions. For example, if the data annotation task has about 3 questions and 1 is neutral, the decider on how the question has been perceived on a sentiment analysis problem is a valid objective. 

- NPS is the difference between positive and negative answers

__Level of Automation__

4. In a decision pipeline, where you've got to choose between Automation and Manual Tasks and also between Accuracy and Mistakes produced, the number of decisions made depends on the Level of Automation applied to the Annotation job.

__KPIs for Productivity__

5. In the topic of Availability, the tools used to obtain the dataset from given format to required format for annotation is a concern of Productivity and hence KPIs come into the problem solving context. 

- Availability of the assist tools for the job such as annotation tools, image recognition tools, spreadsheets depends on how productive the job is for each person. For maximising the productivity the problem must be addressed from the ground base on how the data has been collected and persisted. 

__Customer Satisfaction Score__

6. How secure the job related to applying data is dependent on the satisfaction and dissatisfaction score provided by the customer or the client. So CSS (Customer Satisfaction Score) is a key metric that determines Security.

__Data Bias__

7. Data Bias is a key factor of historical provenance and origins of the data because that is how the trained model will produce its output. 

__Data Formats and Transformation__

8. The Cost on Provenance is dependent on the formats of data and data transformation pipelines that are used. 

_Next we see the Model Building Metrics from the AI Approach_

MODEL BUILDING METRICS
----------------------

- **The Data Value** on **Feature Extraction** depends on: Classification Uncertainty and Consistency
- **The Data Value** on **Hyperparameters** depends on: Completeness
- **The Data Value** on **Tuning** depends on: Accuracy
- **The Data Value** on **Model Selection** depends on: Loss Functions and Model / Information Currency
- **The Data Value** on **Benchmarking** depends on: Validity
- **The Data Management Cost** on **Feature Extraction** depends on: Complexity and Invariancy
- **The Data Management Cost** on **Hyperparameters** depends on: Error Functions
- **The Data Management Cost** on **Tuning** depends on: Test Dataset
- **The Data Management Cost** on **Model Selection** depends on: Model size, Performance and Serialization of Model
- **The Data Management Cost** on **Benchmarking** depends on: Execution Environment
- **The # of Decisions Made** on **Feature Extraction** depends on: Dataset Size

__Classification Uncertainty and Consistency__

1. The data value statistics inferred from feature extracton process is relevant to how the data labels are classified. Classification uncertainty explains why each data item is classified in that data label or class. Consistency is required for such feature extraction process in order to make the process repeatable. 

__Completeness__

2. For example, using grid search cross validation algorithm, you can actually find the hyperparameters of a machine learning algorithm. In finding so, the dataset is aimed towards completeness which is in reality matched with predefined attributes that relate to the dataset. Those pre-defined attributes define the dataset to explain it in a particular way. 

__Accuracy__

3. In Tuning the model, the value obtained denotes that the Accuracy is really the key. 

__Loss Functions and Model / Information Currency__

4. Loss Functions and Data currency of the model or the currency of the information it handles are key factors that help in model selection from one or two different models. 

__Validity__

5. Validation dataset is the key factor that is considered for benchmarking. Benchmarking depends on Validation loss and it is taken into consideration for model selection.

__Complexity and Invariancy__

6. Complexity and Invariancy are cost parameters that enable feature extraction. Cost and complexity drive value whereas invariancy of data transformation helps the model achieve its objectives. 

__Error Functions__

7. Error Functions determine the hyperparameters - Training error must be optimal and bias-variance tradeoff must be balanced. Hyperparameters are chosen in order to navigate the tradeoff between bias and variance. 

__Test Dataset__

8. Additional Test Data in a test dataset helps in tuning the model for performance. This implies there needs to be a measurable dataset and model while tuning the model. 

__Model size, Performance and Serialization of Model__

9. When the model is serialized the performance increases and when the size of the model is optimal, the cost of the model as well reduces. 

__Execution Environment__

10. The execution environment is well dependent on the benchmarking of the model. If the model is run across multi-devices they are to be modified accordingly. The deployment of the model such as to the cloud or the edge varies. 

__Dataset Size__

11. With regards to the dataset size used for training, the inference makes a number of decisions to achieve the objective. Such varied dataset sizes are sourced from bias on data attributes such as labels. So decisions made in the ML or AI pipeline will change accordingly. 


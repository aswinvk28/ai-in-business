## Training and Evaluating a Model

- Overview of Modeling
- Training Data
- Model Evaluation
- Transfer Learning and Automated ML Models act as framework
- Single Neural network (NN) consists of series of computational layers
- Specialised nodes within a NN perform various computations
- Uncertainty is Good for neural Networks to learn
- Backpropagation & Updating the Weights of a Network
- Perceptron Math
- Activation Functions: Sigmoids and ReLUs
    - Decision Boundaries
- Training Data: Currency of Machine Learning
- Unseen data
- Learning by Examples and Patterns of Data
- Examples of a distribution of data

## A Pet Model

- Once the network is trained it retains all the knowledge from the example images
- A new class must be remedied using training of the new class to the model using additional data
- Train it with all types of data
- Use a diverse set of data to build a robust model
- Depending on the intended usage of data, understanding all model scenarios is a must
- While training, Reduce the noise of the data as much as possible
- Common Issues with Training Data
    - Unbalanced or biased data
    - Training Data Distribution
    - Collect more training data for the classes that are lacking, or reduce the amount in large classes
    - Data does not reflect real world data
    - Mislabeled data
    - Insufficient data

## Voice Data Training

- In order to train, we need sufficient data. So the author is talking about data size problem. 

## Training Data

- In ML, Training data is key
- Monitor the petrformance of the model and understand where the model performs low and update the model accordingly

## Model Evaluation

- Where the model is performing well and where it is lacking
- Clear performance metrics
- We need sensible metrics while performing the model
- We need how it will perform when deployed in production
- Out of labeled data: 80% training data and 20% testing model: 10% validation data, 10% test data
- We need to include Correct and incorrect predictions
- How model performs in individual class and also across classes
- F1 score of above 0.7 or 0.8 are considered to be decent
- Confusion Matrix
- Overall Model Recall is average of Recall of individual classes, same goes for Precision

## Model Evaluation Summary

- Model should never see the test data until model evaluation
- Precision and recall are key metrics when evaluating a model
- F1 Score provides an overall measure of model performance
- A confusion matrix can help identify where a model is failing

## Transfer Learning and Automated ML

- Making ML more acceptable to larger audience
- Use case driven and using classes of data or labeled data
- AutoML allows to build relatively robust model without much Machine Learning Experience
- Produce ML Model with AutoML to get real hands-on experience with the model
- We can leverage existing trained models to solve new problems
- Pretrained from online sources
- Automated ML makes it easy to create models
- Complex models require custom development

## Fine Tuning of Model

- Each model has pros and cons
- Idea behind is to leverage previously learned models
- It is much quicker and cheaper to build models by Transfer Learning
- Much less data is required to adjust and tune the model while performing model under Transfer Learning

## Automated ML

- Neural Architecture Search
- Fitting various components of the Neural network together and handle accuracy
- Service to automatically create models from data
- Allows for quick prototyping 
- Benefit of enterprise support
- Much less hassle and complexity
- Automatically determine best architecture for data types
- Consists of architecture blocks that can be configured together for optimization
- Handled by ML Service Provider

## Automated ML vs Custom Modeling

### Automated ML 

- Easy to get started
- Robust enterprise support
- Cheap for quick development

-- Limited use cases

-- Difficult to extend

-- Data is accessible to provider

### Custom Modeling

- Complete customizability
- Unlimited use cases
- Full control over parameter tuning

-- Expensive to get started

-- Requires ML Expertise

-- Limited means of external support


# Introduction to MLOps

In this site I intent to document some of the major points from  the [MLOps Specialization](https://www.coursera.org/specializations/machine-learning-engineering-for-production-mlops) from Coursera.
There is a total of four courses:
  - Introduction to Machine Learning in Production
  - Machine Learning Data Lifecycle in Production
  - Machine Learning Modeling Pipelines in Production
  - Deploying Machine Learning Models in Production

# Course 1: Introduction to Machine Learning in Production

The are foure main stages in the ML deployment process:
Scope -> Data -> Modeling -> Deployment

Kew challenges

- Concept Drift (X -> Y): 
- Data Drift (X): Has the data change? Relates to changes in the distribution of the input data.
- Software issues: 
  - Realt Time application or Batch
  - Cloud vs Edge (cars, mobile, offline)/Browser
  - Compute resources: CPU, GPU, memory
  - Latancy, throughput (Queries per second - QPS) - more info [here](https://www.blazemeter.com/blog/what-relationship-between-users-and-hits-second)
  - Logging
  - Security and Privacy

A nice [Data Drift and Concept Drift](https://towardsdatascience.com/machine-learning-in-production-why-you-should-care-about-data-and-concept-drift-d96d0bc907fb) post.
How to deal with Drift?
  - retrain the model
  - apply weights to new data
  - drop past data if new data is enough
  - tune the model
  - modify business scope, new KPIs definition

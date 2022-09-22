# course-notes
notes for a few online courses

## Project design

Goal
- select and ingest in-depth online courses related to geospatial machine learning and MLOps
- export booklet

Plan
- geospatial ewrqewr



Process
> 

## Milestones


## CS 329S: Machine Learning Systems Design
[syllabus](https://stanford-cs329s.github.io/syllabus.html)

What’s machine learning systems design?
> The process of defining the interface, algorithms, data, infrastructure, and hardware for a machine learning system to satisfy specified requirements (reliable, scalable, maintainable, adaptable).


Questions
```
> You’ve trained a model, now what?
> What are different components of an ML system?
> How to do data engineering?
> How to engineer features? 
> How to evaluate your models, both offline and online?
> What’s the difference between online prediction and batch prediction?
> How to serve a model on the cloud? On the edge?
> How to continually monitor and deploy changes to ML systems?
> …
```

ML in production

```
Choose a metric to optimize
Collect data
Train model
Realize many labels are wrong -> relabel data
Train model
Model performs poorly on one class -> collect more data for that class
Train model
Model performs poorly on most recent data -> collect more recent data
Train model
Deploy model
Dream about $$$
Wake up at 2am to complaints that model biases against one group -> revert to older version
Get more data, train more, do more testing
Deploy model
Pray
Model performs well but revenue decreasing
Cry
Choose a different metric
Start over
```


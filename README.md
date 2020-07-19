# Machine Learning with Python
Source: “An Introduction to Machine Learningwith Python by Andreas C. Müller and Sarah Guido (O’Reilly). Copyright 2017 SarahGuido and Andreas Müller, 978-1-449-36941-5.”

## Setup
* Require Python 3.8.2
```
./scripts/setup.sh
```

## Chapter 1
* Supervised learning: the user provides the algorithm with pairs of inputs and desired outputs, and the algorithm finds a way to produce the desired out‐put given an input
* Unsupervised algorithms: only the input data is known, and no known outputdata is given to the algorithm
* For both supervised and unsupervised learning tasks, it is important to have a repre‐sentation of your input data that a computer can understand. Often it is helpful to think of your  data as a table. Each data point that you want to reason about (each email, each customer, each transaction) is a row, and each property that describes thatdata point (say, the age of a customer or the amount or location of a transaction) is a column
* Each entity or row here is known as a sample (or data point) in machine learning, while the columns — the properties that describe these entities — are called features

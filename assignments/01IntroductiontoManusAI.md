# Assignment 1: Building a Basic Manus AI Script

## Objective

Familiarize yourself with the Manus AI library by writing a script.

## Expected Capabilities

- Understand Manus AI setup
- Create and run AI scripts

## Instructions

### Part 1

**Install Manus AI**

Use pip to install Manus AI package.

```
pip install manusAI
```

**Create Simple Model**

Write a script to initialize and train a simple neural network.

```
import manusAI

model = manusAI.initializeModel('neuralNet')
model.train(data='sample.csv')
```

## Tasks

### Task 1: Initialize and Train Model

Write a script that initializes a neural network and trains it on example data.

```
import manusAI

model = manusAI.initializeModel(layers=3)
model.train(data='data.csv')
```

## Submission Instructions

Submit a screenshot of your script and output.

## Checklist

- [ ] Manus AI Installed
- [ ] Script Written
- [ ] Model Trained
- [ ] Output Verified

## Check for Understanding

**Which command installs Manus AI?**

- conda install AIManus
- pip install manusAI
- npm install manusAI

**Answer:** [Your answer here]

**What is an essential component of starting an AI script?**

- Deploying model
- Running model
- Initializing model

**Answer:** [Your answer here]

**What does manipulating layers in a model affect?**

- Model initialization
- Model performance
- Model storage

**Answer:** [Your answer here]
# ML Fundamentals

This section establishes the conceptual foundation required to understand Machine Learning.

The objective is to develop a clear mental model of how Machine Learning systems work before studying individual algorithms in depth.

The focus is on understanding:

- What Machine Learning is
- Why Machine Learning is useful
- How different types of Machine Learning work
- How data becomes a learning problem
- How models learn from data
- How models generalize
- Why models fail
- How Machine Learning problems should be approached
- How a complete Machine Learning workflow operates

---

# Project Structure

```text
00_ML_Fundamentals/
│
├── README.md
│
├── 01_Introduction_to_Machine_Learning.ipynb
├── 02_Artificial_Intelligence_vs_Machine_Learning.ipynb
├── 03_Machine_Learning_vs_Deep_Learning.ipynb
├── 04_Why_Machine_Learning.ipynb
│
├── 05_Types_of_Machine_Learning.ipynb
├── 06_Supervised_Learning.ipynb
├── 07_Unsupervised_Learning.ipynb
├── 08_Semi_Supervised_Learning.ipynb
├── 09_Reinforcement_Learning.ipynb
│
├── 10_Datasets_Features_and_Labels.ipynb
├── 11_Training_Validation_and_Testing.ipynb
├── 12_Model_Training_and_Inference.ipynb
├── 13_Parameters_and_Hyperparameters.ipynb
│
├── 14_Machine_Learning_Workflow.ipynb
├── 15_Problem_Definition_and_Formulation.ipynb
├── 16_Data_to_Model_Pipeline.ipynb
├── 17_Training_to_Deployment_Lifecycle.ipynb
│
├── 18_Loss_Functions_and_Objective_Functions.ipynb
├── 19_Model_Optimization_Overview.ipynb
├── 20_Generalization.ipynb
├── 21_Overfitting_and_Underfitting.ipynb
├── 22_Bias_and_Variance.ipynb
├── 23_Bias_Variance_Tradeoff.ipynb
│
├── 24_Inductive_Bias.ipynb
├── 25_Model_Complexity.ipynb
├── 26_Regularization_Overview.ipynb
├── 27_Data_Leakage.ipynb
├── 28_Distribution_Shift_and_Dataset_Shift.ipynb
│
├── 29_Model_Assumptions.ipynb
├── 30_Training_Error_and_Test_Error.ipynb
├── 31_Baselines_and_Benchmarking.ipynb
├── 32_Model_Evaluation_Overview.ipynb
│
├── 33_Machine_Learning_Failure_Modes.ipynb
├── 34_Error_Analysis_Overview.ipynb
├── 35_Reproducibility_in_Machine_Learning.ipynb
│
├── 36_Machine_Learning_Problem_Solving_Framework.ipynb
├── 37_How_to_Approach_an_ML_Problem.ipynb
├── 38_Model_Selection_Overview.ipynb
│
├── 39_End_to_End_ML_Workflow_Example.ipynb
├── 40_ML_Fundamentals_Revision.ipynb
└── 41_ML_Fundamentals_Interview_Questions.ipynb
```

---

# Learning Philosophy

The learning process in this section follows:

```text
Concept
   ↓
Intuition
   ↓
Formal Definition
   ↓
Example
   ↓
Practical Perspective
   ↓
Machine Learning Context
```

The goal is not to memorize definitions.

The goal is to build the mental framework required to understand more advanced Machine Learning concepts later.

---

# Learning Path

```text
01–04  → Understanding Machine Learning
05–09  → Learning Paradigms
10–13  → Data and Models
14–17  → Machine Learning Workflow
18–19  → Learning and Optimization
20–28  → Generalization and Model Behavior
29–32  → Evaluation Foundations
33–35  → Failure Analysis and Reliability
36–38  → ML Problem Solving
39     → End-to-End ML Workflow
40     → Revision
41     → Interview Preparation
```

---

# 01 — Introduction to Machine Learning

Understanding the fundamental idea of Machine Learning.

Topics include:

- What is Machine Learning?
- Definition of Machine Learning
- Traditional Programming vs Machine Learning
- Learning from Data
- Models
- Predictions
- Learning Patterns
- Machine Learning Terminology
- Applications of Machine Learning

---

# 02 — Artificial Intelligence vs Machine Learning

Understanding the relationship between Artificial Intelligence and Machine Learning.

Topics include:

- Artificial Intelligence
- Machine Learning
- Deep Learning
- Relationship between AI, ML, and DL
- Differences in approach
- Examples
- Practical applications

---

# 03 — Machine Learning vs Deep Learning

Understanding where Machine Learning ends and Deep Learning begins.

Topics include:

- Classical Machine Learning
- Deep Learning
- Feature Engineering
- Representation Learning
- Data Requirements
- Computational Requirements
- Model Complexity
- Typical Applications

---

# 04 — Why Machine Learning

Understanding why Machine Learning is used instead of traditional rule-based programming for certain problems.

Topics include:

- Rule-Based Systems
- Problems with Explicit Rules
- Pattern Recognition
- Complex Decision Boundaries
- Adaptation from Data
- Automation
- Scalability
- Examples of ML-appropriate problems

---

# 05 — Types of Machine Learning

Overview of the major Machine Learning paradigms.

Topics include:

- Supervised Learning
- Unsupervised Learning
- Semi-Supervised Learning
- Reinforcement Learning
- Self-Supervised Learning
- Comparison of Learning Paradigms

---

# 06 — Supervised Learning

Understanding learning from labeled examples.

Topics include:

- Features
- Labels
- Input
- Target
- Training Examples
- Regression
- Classification
- Learning a Mapping
- Prediction

Detailed algorithms are covered later in the Supervised Learning section.

---

# 07 — Unsupervised Learning

Understanding learning from unlabeled data.

Topics include:

- Unlabeled Data
- Pattern Discovery
- Clustering
- Dimensionality Reduction
- Representation
- Structure Discovery

Detailed algorithms are covered later in the Unsupervised Learning section.

---

# 08 — Semi-Supervised Learning

Understanding learning from a combination of labeled and unlabeled data.

Topics include:

- Labeled Data
- Unlabeled Data
- Why Labels Can Be Expensive
- Semi-Supervised Learning Setup
- Practical Applications
- Advantages and Limitations

---

# 09 — Reinforcement Learning

Understanding learning through interaction and feedback.

Topics include:

- Agent
- Environment
- State
- Action
- Reward
- Policy
- Learning Through Interaction
- Exploration
- Exploitation

Detailed Reinforcement Learning topics are covered later in Advanced Machine Learning.

---

# 10 — Datasets, Features, and Labels

Understanding how real-world problems are represented as Machine Learning datasets.

Topics include:

- Dataset
- Sample
- Instance
- Observation
- Feature
- Feature Vector
- Label
- Target
- Input Space
- Output Space
- Structured Data
- Unstructured Data

---

# 11 — Training, Validation, and Testing

Understanding how datasets are divided during Machine Learning development.

Topics include:

- Training Set
- Validation Set
- Test Set
- Purpose of Each Dataset
- Data Splitting
- Model Selection
- Final Evaluation
- Generalization

Detailed validation strategies are covered later in Model Evaluation and Selection.

---

# 12 — Model Training and Inference

Understanding the difference between learning and prediction.

Topics include:

- Training
- Learning
- Model Parameters
- Inference
- Prediction
- Training Phase
- Inference Phase
- Batch Prediction
- Online Prediction

---

# 13 — Parameters and Hyperparameters

Understanding the difference between values learned by a model and values chosen before training.

Topics include:

- Parameters
- Hyperparameters
- Learning Parameters
- Configuration Parameters
- Examples
- Hyperparameter Tuning Overview

Detailed hyperparameter optimization is covered later.

---

# 14 — Machine Learning Workflow

Understanding the complete Machine Learning development process.

Topics include:

- Problem Definition
- Data Collection
- Data Understanding
- Data Preparation
- Feature Engineering
- Model Selection
- Training
- Validation
- Evaluation
- Error Analysis
- Deployment
- Monitoring

---

# 15 — Problem Definition and Formulation

Understanding how to convert a real-world problem into a Machine Learning problem.

Topics include:

- Business Problem
- Technical Problem
- ML Problem
- Input Definition
- Target Definition
- Objective Definition
- Constraints
- Success Criteria
- Regression Formulation
- Classification Formulation
- Clustering Formulation

---

# 16 — Data to Model Pipeline

Understanding the flow from raw data to predictions.

```text
Raw Data
   ↓
Data Cleaning
   ↓
Feature Construction
   ↓
Dataset Preparation
   ↓
Train / Validation / Test
   ↓
Model Training
   ↓
Evaluation
   ↓
Prediction
```

Topics include:

- Data Pipeline
- Feature Pipeline
- Training Pipeline
- Inference Pipeline
- Data Transformation
- Model Pipeline

---

# 17 — Training to Deployment Lifecycle

Understanding the broader lifecycle of a Machine Learning system.

Topics include:

- Data
- Training
- Validation
- Evaluation
- Model Packaging
- Deployment
- Inference
- Monitoring
- Retraining
- Model Updates

This provides the conceptual foundation for Machine Learning Engineering and MLOps.

---

# 18 — Loss Functions and Objective Functions

Understanding how Machine Learning models measure error.

Topics include:

- Prediction Error
- Loss
- Cost
- Objective Function
- Empirical Risk
- Optimization Objective
- Training Objective

Specific loss functions are studied in depth alongside their respective algorithms.

---

# 19 — Model Optimization Overview

Understanding the basic idea of optimization in Machine Learning.

Topics include:

- Optimization Problem
- Objective Function
- Parameters
- Search Space
- Gradient-Based Optimization
- Gradient Descent
- Learning Rate
- Local and Global Optima

Mathematical optimization is covered in depth in Mathematics for ML.

---

# 20 — Generalization

Understanding the central goal of Machine Learning: performing well on unseen data.

Topics include:

- Training Performance
- Unseen Data
- Generalization
- Generalization Error
- Memorization
- Learning Patterns
- Generalization Gap

---

# 21 — Overfitting and Underfitting

Understanding two fundamental model failure modes.

Topics include:

- Overfitting
- Underfitting
- Symptoms
- Causes
- Training Performance
- Validation Performance
- Model Complexity
- Solutions

---

# 22 — Bias and Variance

Understanding two major sources of prediction error.

Topics include:

- Bias
- Variance
- High Bias
- High Variance
- Model Complexity
- Error Decomposition

---

# 23 — Bias-Variance Tradeoff

Understanding the relationship between model complexity and generalization.

Topics include:

- Bias-Variance Tradeoff
- Underfitting
- Overfitting
- Model Complexity
- Training Error
- Validation Error
- Generalization

---

# 24 — Inductive Bias

Understanding the assumptions that allow a model to generalize beyond its training examples.

Topics include:

- Inductive Bias
- Model Assumptions
- Hypothesis Space
- Prior Assumptions
- Examples of Inductive Bias

---

# 25 — Model Complexity

Understanding how model complexity affects learning and generalization.

Topics include:

- Simple Models
- Complex Models
- Hypothesis Space
- Capacity
- Complexity
- Generalization
- Overfitting

---

# 26 — Regularization Overview

Understanding how additional constraints can help models generalize.

Topics include:

- Regularization
- Model Complexity
- Penalty Terms
- L1 Regularization
- L2 Regularization
- Regularization Strength
- Relationship with Overfitting

Detailed regularization techniques are covered in later sections.

---

# 27 — Data Leakage

Understanding how unintended information can make Machine Learning evaluation invalid.

Topics include:

- Data Leakage
- Target Leakage
- Train-Test Contamination
- Preprocessing Leakage
- Feature Leakage
- Leakage During Model Selection
- Prevention Strategies

---

# 28 — Distribution Shift and Dataset Shift

Understanding what happens when training and deployment data differ.

Topics include:

- Training Distribution
- Test Distribution
- Deployment Distribution
- Covariate Shift
- Concept Drift
- Dataset Shift
- Distribution Shift
- Consequences

---

# 29 — Model Assumptions

Understanding the assumptions behind Machine Learning models.

Topics include:

- Model Assumptions
- Data Assumptions
- Statistical Assumptions
- Independence
- Linearity
- Distributional Assumptions
- Why Assumptions Matter
- Consequences of Violating Assumptions

Detailed assumptions are studied with individual algorithms.

---

# 30 — Training Error and Test Error

Understanding the difference between fitting the training data and performing on unseen data.

Topics include:

- Training Error
- Validation Error
- Test Error
- Generalization Error
- Error Gap
- Model Selection
- Evaluation Bias

---

# 31 — Baselines and Benchmarking

Understanding how to determine whether a Machine Learning model is actually useful.

Topics include:

- Baseline Models
- Simple Baselines
- Random Baselines
- Majority-Class Baseline
- Benchmarking
- Model Comparison
- Improvement Over Baseline

---

# 32 — Model Evaluation Overview

Introducing the major categories of Machine Learning evaluation.

Topics include:

- Regression Evaluation
- Classification Evaluation
- Clustering Evaluation
- Offline Evaluation
- Online Evaluation
- Evaluation Metrics
- Metric Selection
- Evaluation Tradeoffs

Detailed metrics are covered later in Model Evaluation and Selection.

---

# 33 — Machine Learning Failure Modes

Understanding how Machine Learning systems fail.

Topics include:

- Poor Data Quality
- Insufficient Data
- Data Leakage
- Distribution Shift
- Overfitting
- Underfitting
- Wrong Features
- Wrong Objective
- Wrong Metric
- Model Bias
- Deployment Failures

---

# 34 — Error Analysis Overview

Understanding how to systematically investigate model errors.

Topics include:

- Error Analysis
- Error Categories
- False Predictions
- Failure Patterns
- Data Quality Problems
- Feature Problems
- Model Problems
- Evaluation Problems
- Improving Models Through Error Analysis

---

# 35 — Reproducibility in Machine Learning

Understanding how to make experiments repeatable and trustworthy.

Topics include:

- Random Seeds
- Dataset Versions
- Environment Management
- Dependency Management
- Configuration
- Experiment Records
- Code Versioning
- Reproducible Experiments

---

# 36 — Machine Learning Problem-Solving Framework

A structured framework for solving Machine Learning problems.

```text
Understand the Problem
        ↓
Define the Objective
        ↓
Understand the Data
        ↓
Establish a Baseline
        ↓
Prepare the Data
        ↓
Select Candidate Models
        ↓
Train
        ↓
Evaluate
        ↓
Analyze Errors
        ↓
Improve
        ↓
Validate
        ↓
Deploy
        ↓
Monitor
```

---

# 37 — How to Approach an ML Problem

A practical decision-making framework.

Topics include:

- Understanding Requirements
- Defining the Target
- Choosing the Learning Paradigm
- Choosing Evaluation Metrics
- Establishing Baselines
- Selecting Candidate Models
- Designing Experiments
- Interpreting Results
- Error Analysis
- Iterative Improvement

---

# 38 — Model Selection Overview

Understanding how to choose models intelligently.

Topics include:

- Problem Type
- Dataset Size
- Feature Types
- Interpretability
- Computational Constraints
- Training Cost
- Inference Cost
- Model Complexity
- Accuracy Requirements
- Baseline Comparison

---

# 39 — End-to-End ML Workflow Example

Applying the concepts from this section to a complete Machine Learning problem.

The example should demonstrate:

```text
Problem
   ↓
Data
   ↓
Problem Formulation
   ↓
Train / Validation / Test
   ↓
Baseline
   ↓
Preprocessing
   ↓
Model
   ↓
Training
   ↓
Evaluation
   ↓
Error Analysis
   ↓
Model Improvement
   ↓
Final Evaluation
```

The purpose is to connect the individual concepts into one complete mental model.

---

# 40 — ML Fundamentals Revision

A consolidated revision resource covering the most important concepts from this section.

Includes:

- Important Definitions
- Core Concepts
- Learning Paradigms
- ML Workflow
- Generalization
- Overfitting
- Underfitting
- Bias-Variance
- Inductive Bias
- Data Leakage
- Model Selection
- Evaluation Concepts
- Failure Modes

---

# 41 — ML Fundamentals Interview Questions

Placement-oriented questions based on the concepts covered in this section.

Topics include:

- Machine Learning Fundamentals
- Supervised vs Unsupervised Learning
- Training vs Testing
- Parameters vs Hyperparameters
- Overfitting vs Underfitting
- Bias vs Variance
- Generalization
- Data Leakage
- Model Selection
- Evaluation
- ML Workflow
- Real-World ML Scenarios

The objective is to explain concepts clearly rather than memorize predefined answers.

---

# Prerequisites

Before starting this section, it is recommended to have basic knowledge of:

- Python Programming
- Basic Data Structures
- Basic Mathematics
- Basic Statistics

Detailed mathematical foundations are developed separately in:

```text
01_Mathematics_for_ML/
```

Python-specific Machine Learning preparation is maintained separately in the Python repository.

---

# Outcome

After completing this section, you should be able to:

- Explain what Machine Learning is
- Distinguish major Machine Learning paradigms
- Formulate real-world problems as ML problems
- Understand datasets, features, labels, and targets
- Explain training, validation, and testing
- Understand how models learn and make predictions
- Explain overfitting and underfitting
- Understand bias and variance
- Explain generalization
- Identify data leakage
- Understand model assumptions
- Establish baselines
- Understand the purpose of model evaluation
- Perform basic error analysis
- Approach an ML problem systematically
- Explain the complete Machine Learning lifecycle

This section provides the conceptual foundation for the deeper mathematical, algorithmic, experimental, and engineering topics covered throughout the rest of the repository.
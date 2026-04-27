# Forgery Detection for Handwritten Signatures

## An Overview of Our Dataset
Our starting dataset includes images of real and forged handwritten signatures (for 30 people). When we create our own dataset, we will have the real signatures of our team members, as well as forged signatures. We plan to initially work with the following kaggle dataset: https://www.kaggle.com/code/nymikapasnoori/signature-forgery-detection/input?select=sample_Signature, and then we will supplement this by gathering our own data. 

In this dataset, there seems to be 480 observations that include forged and real observations of handwritten signatures. We are working to predict a binary variable (forged vs. real), so our predictors will be binary. Since this is a computer vision task, our images don't have specific numerical variables for input.

## Our Potential Research Questions
We are interested in predicting whether or not a signature is forged (potentially expand to handwriting in general). 
- Can we detect forgery?
- How well can we detect forgery?

Using predictive modeling, we intend to take an image and then output 0 or 1, depending on if the signature is classified as forged or authentic. We are working on figuring out the implementation details and the best way to classify (with comparing, storing authentic signs in the database so the model has a baseline to compare off of).

## Our Proposed Project Timeline

**Week 4**: Load and Collect the Data

**Week 5**: Split data into training and testing sets and begin exploratory data analysis on the dataset, creating visuals to analyze trends in the variables, Select features of importance and engineer features

**Week 6**: Build model using features, Evaluate initial models on training dataset using cross-validation

**Week 7**: Refine and tune model using training dataset

**Week 8**: Use testing data on the best model and begin the write-up process

**Week 9**: Create presentation

**Week 10**: Present

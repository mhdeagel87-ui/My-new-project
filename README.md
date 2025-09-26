# My-new-project
Building AI course project
# SmartPet Classifier

Final project for the Building AI course

## Summary

This project uses a simple neural network to predict whether an animal is a dog or a cat based on input features like height, weight, and body length.  
Building AI course project.

## Background

Identifying animals quickly and accurately can be useful in many contexts, such as:
* Animal shelters needing faster intake processing
* Veterinary assistants who want a quick reference tool
* Training datasets for computer vision projects

I chose this project because it’s a fun and concrete way to learn about machine learning classification, and pets make the examples engaging.

## How is it used?

Users input numerical values for height, weight, and length.  
The trained model then predicts whether the animal is a dog or a cat, returning a probability score.  

Example use cases:
* On a desktop app for educational purposes  
* As a backend model for a mobile app in shelters  

Example illustration:  
![Cat example](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

## Data sources and AI methods

Training data could come from:
* Publicly available animal measurement datasets
* Self-collected structured data  

The method:  
* Logistic regression as a baseline  
* Neural network with a sigmoid activation in the output layer  

| Feature   | Example value |
|-----------|---------------|
| Height    | 35 cm         |
| Weight    | 8 kg          |
| Length    | 60 cm         |

## Challenges

* Doesn’t capture breeds or special cases (very small dogs vs. large cats).  
* Ethical considerations: shouldn’t be used in real veterinary diagnosis or as a substitute for professional evaluation.  
* Data imbalance (more dog data than cat data may skew results).  

## What next?

Future improvements could include:  
* Expanding the dataset to more animals (e.g. rabbits, hamsters).  
* Using computer vision (image classification) instead of manual measurements.  
* Deploying as a web app with user input forms.  

## Acknowledgments

* Inspired by the **Building AI course** by University of Helsinki and Reaktor  
* [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)  

# Cyber Attack Detection in Water Distribution Systems

## Project Overview

With the global increase in cyber attacks by 38% in 2022, and considering the crucial nature of water utility systems, the need for robust cybersecurity measures is more crucial than ever. This project aims to predict and prevent cyber attacks in water distribution systems by detecting them based on sensor readings. We're also analysing the feature importance among the different sensors deployed within the network.

We're developing a classification method leveraging four primary models:

1. Logistic Regression 
2. Random Forest 
3. Gradient Boosting 
4. Neural Networks
   
All models are carefully calibrated via hyper-parameter tuning and cross-validation. However, to control the total runtime, the Neural Network model will not use cross-validation.

## Getting Started

### Prerequisites

- Python 3.x
- Libraries: sklearn, numpy, pandas, keras (for Neural Networks)

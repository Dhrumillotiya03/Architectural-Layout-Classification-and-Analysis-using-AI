# Architectural-Layout-Classification-and-Analysis-using-AI

## Question Statement
An architecture company has recently completed an initiative to digitalize their building layout designs. As part of this
exercise, they have converted the plan view of buildings architected by them into bitmaps of size 640 x 480 pixels, as
shown by the sample images below.They are now ready to launch initiatives to use this data to improve their productivity, and facilitate robust designs.
They are also very keen to mine the information potentially hidden in these views, and establish new and innovative
processes to respond rapidly to customer requirements and demands. They are convinced that methods of Data
Science in general, and Machine Learning in particular, can be effectively used to achieve these goals. Following are
some of the requirements / questions they have posed:  
1. We have a hunch that our designs can be grouped into families, based on their shapes. Knowledge of these
families will not only improve our insights into our own designs, but also help in standardizing them by
creating design templates. We have been informed that multiple approaches can be used to do this, and we
would like to see the results of at least two approaches.  
2. Further, we would like to classify the complexity of layouts as Low Complexity, Medium Complexity, High
Complex. Based on a formal analysis of the layouts we would like to create the criteria to decide their
complexity. Can you carry out an appropriate analysis, establish the criteria, and classify the layouts?  
3. We are very keen to speed up our layout design process by retrieving relevant prior layouts based on a set of
gross parameters. For example, the architect usually knows the dimensions (length, width) of the tight-fitting
box (see Appendix 1), the layout area, and the permissible layout complexity. When the architect specifies
these parameters, the design family / families likely to provide the closest designs should be predicted.
Layouts from such families can be retrieved for further detailing.

## Design Family Identification:
 Goal: Group designs by shape for better standardization.  
 Methods: Use clustering and deep learning to categorize similar designs.
 
## Layout Complexity Classification:
 Goal: Define complexity levels for better understanding.  
 Plan: Analyze designs and use machine learning to classify complexity.
 
## Layout Retrieval for Faster Design:
 Goal: Quickly find past designs based on parameters.  
 Solution: Develop a system to predict suitable design families.

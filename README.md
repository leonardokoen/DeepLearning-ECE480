# DeepLearning-ECE480

## Network Anomalies Detection for Live Video Streaming events

Live video streaming has become a mainstay as an essential communication solution
for large enterprises. Fortune-500 companies organize live video streaming
events for several purposes, such as training employees, announcing product releases,
and so on. Accounting for the high value of live video streaming services,
companies invest a significant amount of their annual budgets. Therefore, large
enterprises expect the viewers that participated in the event to receive highquality
video, while being fully engaged. However, in the real-world setting
there are several factors hindering the video quality and user engagement, for
example, the bandwidth limitations when several employees attend an event
simultaneously at several offices, the time when the event is scheduled, and so
on.
Hive Streaming AB provides a software-only solution to deliver high-quality
video stream to Fortune-500 companies. During the event, our software collects
various data regarding the viewers’ quality of experience and behavior. Based
on the reported data, we are able to calculate both the viewer’s engagement and
quality of experience at any specific timestep of the event.
In this assignment, you will have to opportunity to i) analyze, ii) clean, and iii)
transform real-world data. Given data from different events and customers, you
will have to create a machine learning model that detects events with anomalous
behavior.

## Assignment
The assignment is divided in two main parts: i) the data analysis, and ii) the
modeling.

### Data Analysis - Part 1
In this part of the assignment, you will perform data analysis to extract valuable
insights from the dataset. In particular, you are interested in extracting the
following figures:  
• Viewers’ engagement distribution over time, taking into account the customer
id/country/city parameters.  
• Viewers’ QoE distribution over time, taking into account the customer id/country/city
parameters.    
• Viewers’ engagement/QoE distribution differences based on the viewer type
parameter.   
• Viewers’ engagement level duration over country/city/viewer type.     
• Countries/Cities that follow different distributions per customer.    
• Correlations between the data points mentioned in Section 2.  
• Correlations between viewer engagement and the following factors: i)
Number of viewers during the event, ii) Day of the event, iii) Duration of
the event, iv) Countries, v) Viewers’ retention (how much time did each
viewer participated in the event)  

### Modeling - Part 2  
Based on the analysis of Part 1, you are now ready to start the modeling part
of the assignment. In this part, you will have to implement a deep learning
architecture that gets as an input the data points described in Section 3.1. The
model should be able to accurately detect if there is a network anomaly(ies) in
an event.  
Given that the problem can be solved in multiple ways, you are free to apply
any deep learning architecture that you have learned in the course. However, as
a final outcome of this assignment you need to provide a report that addresses
the main points bellow:   
• Which features did you select as input to the model. You need to justify
why you selected these features.   
• Which deep learning architecture did you employ and why you selected
this specific architecture.   
• Which loss function did you select to train the model.   
• How did you train the model, including hyperparameter tuning, dataset
split, and so on.   
• Which metric did you apply to evaluate the performance of the deep learning
model.   


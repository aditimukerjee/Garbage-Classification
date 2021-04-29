# Garbage-Classification

With the following distribution:

- Blue bin (recyclable): 2,398 images
- Green bin (compostable): 826 images
- Black bin (landfill): 844 images

An inception V3 transfer learning model is deployed along with the data augnmentation in Keras and Tensorflow. 
Adadelta is used as the optimizer.

Conclusions:
- The training accuracy is 84.9% and the validation accuracy is 84%
- The test accuracy is 86% and the loss is 0.4.

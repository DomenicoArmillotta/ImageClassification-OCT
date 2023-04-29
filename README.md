# OCT image classification with KERAS
## OBJECTIVE
The aim of this demo is to show the potential of image recognition in the medical field, using a dataset and deep learning techniques.
These methods could in the future assist the medical specialist by reducing cognitive effort and decreasing error, especially in ambiguous situations.
where the disease is in its infancy and therefore barely visible.

## `ISSUE `  --> Solved 
The main problem encountered, that keras is used for small datasets, is it has much lower performance than tensorflow or pyTorch.
This is why the training took too long, so for an implementation of a problem with real objects and images, it is not advisable to use the keras framework.
Here you can see the benchmarks between pyTorch and keras (https://wrosinski.github.io/deep-learning-speed-vol1/).
So it was decided to switch to pyTorch , to implement models with a framework also used in research and corporate. 
keras has the characteristic of being easier to use and organise, but given its low performance, being a high-level framework, we were forced to change the framework.
That is why the explainability and the various tests of the written architectures were not continued.
The report below will describe the work done in the first moments, up to the interruption. The report and all the precautions taken with regard to the code have been scrupulously reviewed, trying to bring the keras framework to its full potential. 
Work has not been interrupted, but implementations using pyTorch will appear in the near future.


## PyTorch
To improve performance in the training and to have more model customization , it's used the framework pyTorch , and in this model the precision is around 80% , but the project is still in progressing

## READ REPORT FOR ALL DETAILS


# Data Mining & Machine Learning: Assessment 2

## Supervised Learning

This coursework was designed to give experience with:

 - Overfitting: finding a classifier that does very well on training data doesn’t mean it will do well
on unseen (test) data.
 - The relationship between overfitting and complexity of the classifier – the more degrees of freedom
in a classifier, the more chances it has to overfit the training data.
 -  The relationship between overfitting and the size of the training set.
 - Bespoke machine learning: it is not always about using just one of the standard types of classifier – the
application may specifically require a certain type of classifier, and it may be wise to develop algorithms that
find the best possible such classifier.

---

For this assessment we have worked with the a dataset sample from Stallkamp et al's *German Street Sign Recognition Benchmark* which consists of:
 - 10 classes
 - 12660 images (converted in grey-scale with pixel values ranging from 0 to 255 abd rescaled to 48*48px)
 
 The 10 labels to predict were:
 
  0. **speed limit 60**
  1. **speed limit 80**
  2. **speed limit 80 lifted**
  3. **right of way at crossing**
  4. **right of way in general**
  5. **give way**
  6. **stop**
  7. **no speed limit general**
  8. **turn right down**
  9. **turn left down**
  
  ---
  
 Split in two parts, this coursework focused on Decision Tree Learning as well as Neural Networks for this classification task.
 For the decision tree, we tried multiple sklearn models:
  - Decision Tree Classifier
  - Random Forest
  - Extra Trees
  
  For the Neural Network, we worked on simple MLP architecture, varying its hyperparameters. 
  
  However, similarly than for the CW1, we undertook the completion of a *research quetion*. For this, we benchmarked CNN architectures with two models:
   - A basic from scratch architecture
   - A second one using transfer learning with the InceptionV3 model
  

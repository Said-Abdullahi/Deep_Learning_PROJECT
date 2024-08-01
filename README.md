**Deep Learning Project: Smart Recycling**

**Overview**
This repository contains the a project from my Master of Data Science degree, this assignment is to feedback on my learning in deep learning theory and its application to data analytics or artificial intelligence problems.

**Task 1 (P Task) Smart Recycling using Deep Learning**
In Assignment 1, I tackled the image classification problem in Fashion-MNIST. There, you used a Densely Connected Neural Network. In Assignment 2, I will apply the best practices of deep-learning computer vision to make something useful for our planet—waste classification.

Background Every day, we put things into our recycle bin, to reduce landfill waste. However, we may unintentionally contribute to recycling contamination by "wish recycling" the wrong items. As every city council has slightly different rules for recycling, you will build a technological solution to ensure you only recycle things that are permitted by your local council. More discussions about recycling contamination can be found here. Recycling rule of a local council (source: Whitehorse City Council)

**Task 1.1 Define a problem**
Define an image classification problem that may help people better recycle, particularly by reducing contamination.

Describe the desired inputs and outputs, including the target classes.

**Task 1.2 Make a plan**
What dataset can you use to develop a deep learning solution?

How many images do you need? How many for training? How many for testing?

**Do you need to label the images yourself?**

How do you determine if your model is good enough?

**Task 1.3 Implement a solution**
Collect relevant data. Develop a deep learning model. Report the model performance against the success criteria that you define.

**Task 2 (C Task) Analyse and improve the model**
**Task 2.1 Build an input pipeline for data augmentation**
Build a data preprocessing pipeline to perform data augmentation. (You may use Keras ImageDataGenerator or write your own transformations.)

Report the model performance with the pipeline added. How much performance gain have you achieved?

Profile your input pipeline to identify the most time-consuming operation. What actions have you taken to address that slow operation? (Hint: You may use a profiler such as the TensorFlow Profiler.)

**Task 2.2 Compare the performance under equal training time**
You may notice that with your pipeline, the model performance improves, but at the cost of a longer training time per epoch. Is the additional training time well spent? Compare the dynamic of model performance (e.g., classification accuracy on the test data) with and without data augmentation, when equal training time is spent in the two scenarios.

**Task 2.3 Identifying model strength and weakness**
Identify images that are incorrectly classified by your model. Do they share something in common? How do you plan to improve the model's performance on those images?

**Task 3 (D Task) Improve model generalisability across domains**
So far, you have used training and test images from the same source (via random data split). Now collect new test images from a different source. For example, you may take some photos yourself if you used downloaded images before. Otherwise, you may take new photos using a different mobile phone or against a different background.

Show sample images from the original test data and the newly collected test data. In what ways are they different?

Feed the new test data into your model. Report the performance change.

Improve your model so that it generalises better on unseen test images.



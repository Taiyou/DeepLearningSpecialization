# Structuring Machine Learning Projects
by Andrew Ng.

About this Course
You will learn how to build a successful machine learning project. If you aspire to be a technical leader in AI, and know how to set direction for your team's work, this course will show you how.

Much of this content has never been taught elsewhere, and is drawn from my experience building and shipping many deep learning products. This course also has two "flight simulators" that let you practice decision-making as a machine learning project leader. This provides "industry experience" that you might otherwise get only after years of ML work experience.

After 2 weeks, you will: 
- Understand how to diagnose errors in a machine learning system, and 
- Be able to prioritize the most promising directions for reducing error
- Understand complex ML settings, such as mismatched training/test sets, and comparing to and/or surpassing human-level performance
- Know how to apply end-to-end learning, transfer learning, and multi-task learning

I've seen teams waste months or years through not understanding the principles taught in this course. I hope this two week course will save you months of time.

This is a standalone course, and you can take this so long as you have basic machine learning knowledge. This is the third course in the Deep Learning Specialization.
# Week 1
**1. Setting up your goal**
- Orthogonalization: extraction of features which are as mutually independent as possible.
- Sngile number evaluation metric: Recall, Precision, and Harmonic mean.

These measures are to show performance.

- Satisficing and Optimizing metric:

Optimizing measure to get as high as possible while satisficing measure should be about sufficient conditions.

eg. Accuracy (Optimizing metric) and calculation time (Satisficing metric)

- Train/dev/test distributions

Aim to choose ditributions of test dataset which corresponding to distributions of training datasets.

- size of the dev and test sets

Old way is to divide data into training and test sets with leave-one out style.
However, in the recent machine learning framework, most of the data is utilized to train an algorithm (might be over 99%).



# Week 2

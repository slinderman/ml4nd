# Introduction

With modern electrophysiological and optical recording techniques, neuroscientists routinely measure the activity of  thousands of cells simultaneously.  Coupled with high-resolution behavioral measurements, these datasets offer unprecedented opportunities to learn how neural circuits function.  This book covers machine learning methods for analysing such datasets, including:
- **spike sorting** and **calcium deconvolution** techniques for extracting relevant signals from raw data
- **markerless pose tracking** methods for estimating animal pose in behavioral videos
- **generalized linear models** for studying neural encoding properties
- **Bayesian decoders** for inferring behavior from neural data
- **point processes** for modeling neural spike trains
- **state space models** for analysis of high-dimensional neural and behavioral time-series
- **sequential variational autoencoders**, like LFADS, for modeling neural dynamics.

The book includes both chapters and coding labs. Each chapter develops the theory behind modern models and algorithms for neural data. The chapters are organized into three units:
1. **Signal Extraction**: methods for extracting spike trains or pose estimates from raw data
2. **Encoding and Decoding**: techniques for relating neural activity to sensory or behavioral covariates
3. **Unsupervised Learning**: models for uncovering low-dimensional structure in high-dimensional neural and behavioral data.

In the **coding labs**, you will hone your programming skills and develop practical understanding by implemeting these methods _from scratch_ (with starter code!) and applying them to _real datasets_.

This book accompanies a course I teach at Stanford University called [STATS 320: Machine Learning Methods for Neural Data Analysis](https://explorecourses.stanford.edu/search?view=catalog&filter-coursestatus-Active=on&page=0&catalog=&academicYear=&q=STATS+320&collapse=). Unfortunately, video recordings of the lectures are not available online. Likewise, I am not currently releasing solutions to the labs, though I may change that in the future!

The book is a work in progress, but I hope you can already begin to enjoy it. Please reach out with any feedback!
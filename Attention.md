# Introduction #
Describes how to install, use and experiment with the Bayesian model of attention

# Getting the code #
You can obtain a read-only version of the code using the following:
```
svn checkout http://sharat-cbcl.googlecode.com/svn/trunk/attention 
```
If you would like to contribute code/bug-fixes as well, please send me an e-mail to obtain read/write access to the repository.

## Dependencies ##
  * You will need a working model of a matlab
  * The code relies upon the BNT-toolbox to perform inference. There is a local copy checked in. However, if you need the latest updates go to http://code.google.com/p/bnt/

# Details #
The code is organized as follows (as now only code listed here is supported)

**attention/**
```
test_spatial_invariance.m  Demonstrates spatial invariance properties of the model.
test_spatial_attention.m   Demonstrates spatial attention in the model.
test_popout.m              Demonstrates popout using orientation features.
test_color_popout.m        Shows that pop-out is independent of feature dimension
test_feature_attention.m   Demonstrates feature-based attention in the model.
test_tuning.m              Shows multiplicative modulation under attention
test_constrast.m           Shows change in contrast response under attention
```
# Support #
Please submit all questions, concerns to http://groups.google.com/group/sharat-code .Please prefix [bayes](bayes.md) to your posts for easier search.
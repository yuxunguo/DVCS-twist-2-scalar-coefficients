
# DVCS-twist-2-scalar-coeffcients

This document contains all the scalar coefficients defined in [arxiv:2109.10373](https://arxiv.org/abs/2109.10373), which is written in Mathematica and with the help of FeynCalc package, check [FeynCalc](https://feyncalc.github.io/) for installation and more details about FeynCalc.

## Guideline

The notebook should be quite self-explanatory itself. The general steps needed to calculate all the coefficients are

0. Install [Mathematica](https://www.wolfram.com/mathematica/) and [FeynCalc](https://feyncalc.github.io/) package. The version that get tested is Mathmatica 12.3.0.0. and FeynCalc 9.3.1.

1. Run through the Initialization Chapter, so all the scalar coefficients will be calculated using FeynCalc.

2. There are two types of scalar coefficients: the ones without light cone vectors and the ones with light cone vectors which require a bit different treatment (which are shown in the note book as well):

   - For the ones without light cone vectors, besides form factors and fine structure constant, the expressions will be functions of proton mass M, Beam energy loss parameter y, Bjorken vaiables xB, momentum transfer t and photon virtuality Q which are given by the kinematics. Thus, those expression are ready to use themselves.
   
   - For the ones with light cone vectors, besides the quantities above they include the skewness parameter xi and our two parameters alpha and beta that control the direction of light cone vectors, so explicit substitutions of xi (\[xi]sub) and alpha and beta are required as well which are shown in the code.



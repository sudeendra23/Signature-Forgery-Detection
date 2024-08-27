# Signature-Forgery-Detection

## 1. Introduction

Signature  verification  and  forgery  detection  is  the  process  of  verifying  signatures  automatically  and  instantly  to determine  whether  the  signature  is  real  or  not.  There  are  two  main  kinds  of  signature  verification:  static  and dynamic.  Static,  or  offline  verification  is  the  process  of  verifying  a document  signature  after  it  has  been  made, while  dynamic  or  online  verification takes  place  as  a  person  creates  his/her  signature  on  a  digital tablet  or  a similar  device.  The  signature  in  question  is  then  compared  to previous  samples  of  that  person's  signature,  which set  up  the  database.  In the  case  handwritten  signature  on  a  document,  the  computer  needs  the samples  to  be scanned  for  investigation,  whereas  a  digital  signature  which  is  already  stored  in  a  data  format  can  be  used  for signature  verification.  Handwritten  signature  is  one  of  the  most  generally  accepted  personal  attributes for verification with identity whether it may for banking or business.

## 2. Importance of signature verification

Signature verification is an important biometric technique that aims to detect whether a given signature is genuine or forged. It is essential in preventing falsification of documents in numerous financial, legal, and other commercial settings. This is a comparative analysis of different already known deep learning architectures to check which of those performs the best on the classification. It was solely for offline handwritten signatures.

## 3. Dataset used

CEDAR-Dataset from kaggle ([here](https://www.kaggle.com/datasets/shreelakshmigp/cedardataset))

## 4. Proposed Methodology

The  handwritten  signature  is  a  behavioral  biometric  which  is  not  based  on  any  physiology  characteristics  of  the individual signature but on the behavior that change over time. Since an individual's signature alters over time the verification and authentication for the signature may take a long  period which includes the errors to be higher in some  cases.  Inconsistent  signature  leads  to higher  false  rejection  rates  for  an  individual·  who  did  not  sign  in  a consistent way.

## 5. Implementation

In  this  application,  we  use  CNNs which  is  a  class  of  deep,  feed forward  artificial  neural  networks that  has  successfully  been  applied  to analyzing  visual  imagery.  CNNs  were  inspired  by  biological  processes  in that the connectivity pattern between neurons resembles the organization of the animal visual cortex.

## 6. Model Architecture

![image](https://github.com/Balusu-Revanth/Signature-Forgery-Detection/assets/128140052/3f282c47-12be-4a09-9457-6d433f610f71)

## 7. Results

In this implementation we were able to **95.4%** accuracy on our test dataset

## 8. Web App Demo

![Animated GIF-downsized](https://github.com/Balusu-Revanth/Signature-Forgery-Detection/assets/128140052/28f8e7ed-9454-4eb6-a35e-5dfbb8087e03)


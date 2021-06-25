# CNN_Resudial_connection
## 1) Dict_merg.ipynb

This notebook contains a function merg_dicts, this function merges the two dictianries and gives a resultant dictianry and if there are any common keys shared between the two dictionaries, the new dictionary's key will have a LIST of the values obtained from both the dictionaries.

## 2) SVHN.ipynb

This notebook contains a CNN model for calssification of SVHN dataset with following fearues
  - Residual connections
  - Dropout layers

### Preprocessing steps followed
i)  Gloabal contrast normalization has been implemented refrenced from "Best Practices for Convolutional Neural Networks
Applied to Object Recognition in Images" paper. https://arxiv.org/pdf/1910.13029.pdf
ii) Normalization of the intensity of the data as been implemented refrenced from "Reading Digits in Natural Images with Unsupervised Feature Learning" paper http://ufldl.stanford.edu/housenumbers/nips2011_housenumbers.pdf


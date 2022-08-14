# Residual-UNet-for-Left-Ventricle-segmentation
This repository related to our article: 
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8382035/ in which a new concept called residual learning is utilized to improve the performance of deep learning schemes against gradient vanishing problems. For this purpose, the Residual Network of Residual Network (i.e., Residual of Residual) substructure is utilized inside the main deep learning architecture (e.g., Unet), which provides more significant detection
indexes. 

<img src="/images/ROR_Unet.jpg" alt="Alt text" title="Optional title">

Results and Conclusion: The proposed method’s performances and its alternatives were evaluated on Sunnybrook Cardiac Data as a reliable dataset in the left ventricle segmentation. The results show that the detection parameters are improved at least by 5%, 3.5%, 8.1%, and
11.4% compared to its deep alternatives in terms of Jaccard, Dice, precision, and false-positive rate indexes, respectively. These improvements were made when the recall parameter was reduced to a negligible value (i.e., approximately 1%). Overall, the proposed method can be used as a suitable tool for more accurate detection of the left ventricle in MRI images.

<img src="/images/Result.png" alt="Alt text" title="Optional title">


## Getting Started

### Prerequisites

* Keras 2.0
* opencv for python
* Theano / Tensorflow / CNTK

  $ pip install -r requierments.txt
  
  $ python setup.py install
  
### Training
For training and evaluating please run codes in the related jupyter files.

# Reference
https://github.com/divamgupta/image-segmentation-keras

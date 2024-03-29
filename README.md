# Plant-Species-Identification
# Automated Plant Species Identification

This repository presents results of our work to predict plant species based on the image of leaf using deep learning. The results are available in the [Notebook](https://github.com/naneja/plants/blob/master/02_Train.pdf)
 
### Implementation
We implemented transfer learning using Alexnet with PyTorch. The following hyperparameters provided best accuracy of 91.7%.

Arch = 'alexnet'; Batch = 32; Hidden_units = 4096; Epochs = 200; Dropout = 0.5; Learning Rate = 0.01, Optmizer = SGD, Momentum = 0.9

## Results
Following Graphs show Model Accuracy for Training and Testing Phase; Model Loss for Training and Testing Phase; and Computation Time for Training the model and Training plus Tresting the model.

![Model](https://github.com/naneja/plants/blob/master/figs/model.png)

## Sanity Check
![Output](https://github.com/naneja/plants/blob/master/figs/output.png)

## Dataset
Our experimental dataset has following 11 types of plants.

| Folder ID | Plant Name |
|:-------------:|:-------------:|
| 1   | Acalypha hispida [EUPHORBIACAE] |
| 2   | Bauhinia coccinea [FABACEAE] |
| 3   | Calotropis gigantea [APOCYNACEAE] |
| 4   | Clitoria ternatea [FABACEAE] |
| 5   | Dillenia suffruticosa [DILLENIACEAE] |
| 6   | Ficus deltoidea [MORACEAE] |
| 7   | Melastoma beccarianum [MELASTOMATACEAE] |
| 8   | Melastoma malabathricum [MELASTOMATACEAE] |
| 9   | Melastoma malabathricum var alba [MELASTOMATACEAE] |
| 10 | Passiflora foetida [PASSIFLORACEAE] |
| 11 | Petrea volubilis [VERBENACEAE] |

### Dataset Size
We created [dataset](https://www.dropbox.com/sh/t4j8t6kb7tozs0b/AAD1J0zsBrHTlIUR2BWcd71Ma?dl=0) of 740 images from 11 plants and the dataset was divided into 596 images for training the model and 144 images used for testing the model.


## Feedback
Please submit your feedback to [Nagender Aneja](http://expert.ubd.edu.bn/nagender.aneja). Please write an email (nagender.aneja@ubd.edu.bn) if you are interested to impement the model in a mobile app or web app. We welcome people and organization who can provide more data on plants from different countries to join this project. 

## Project Members
*  [Dr. Nagender Aneja](http://expert.ubd.edu.bn/nagender.aneja), nagender.aneja@ubd.edu.bn
*  Dr. Somnuk Phon-Amnuaisuk  somnuk.phonamnuaisuk@utb.edu.bn
*  [Dr. Sandhya Aneja](http://expert.ubd.edu.bn/sandhya.aneja), sandhya.aneja@ubd.edu.bn
*  [Dr. Hj Abd Ghani bin Hj Naim](http://expert.ubd.edu.bn/ghani.naim), ghani.naim@ubd.edu.bn
*  [Dr. Rahayu Sukmaria binti Hj Sukri](http://expert.ubd.edu.bn/rahayu.sukri), rahayu.sukri@ubd.edu.bn
*  Rodzay bin Hj Abd Wahab  rodzay.wahab@ubd.edu.bn 
*  Nurul Hazlina binti Hj Zaini, hazlina.zaini@ubd.edu.bn


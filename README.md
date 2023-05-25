# One Hot Encoding - Convolutional Neural Network
This directory includes the results of running the CNN on OHE on the following taxonomic levels: PHYLUM, CLASS, ORDER, FAMILY and GENUS. There are 4 files, corresponding to the result of training, validating and testing with the 4 datasets created in the Data Preparation phase (5% cut-off with ambiguous nucleotides, 5% cut-off without ambiguous nucleotides, 1% cut-off with ambiguous nucleotides, 1% cut-off without ambiguous nucleotides).
To optimize both running time and the F1 score, the models based on 3mers, 4mers, and 5mers were trained for different numbers of epochs. The 3mer model was trained for 200 epochs, the 4mer model for 100 epochs, and the 5mer model for 25 epochs. These specific epoch numbers were chosen as they represented a sweet spot between achieving satisfactory F1 scores while keeping the training time manageable. To ensure fair comparison and unified results, each 3mer model was trained for the same number of epochs, and the same principle applied to the 4mer and 5mer models as well.

# Intended Use of the Product: 

Alzheimer's disease is a debilitating condition in which there is marked volumetric decrease in the Hippocampus in patient's afflicted with the disease. The degradation of the Hippocampus is associated with memory and the disease progression. A 3D image segmentation model be able to quantify the extent of the changes, and provide an automated method of this solution. 

By creating an end-to-end system that can quantify the volume of the Hippocampus, it will be possible to track the disease prograssion. This algorithm can be used to perform expert-level assessment, and assist clinicians in tracking the disease. 

# About the Training Data:

The training data consists of NIFTI files of T2 Magnetic Resonance Imaging of the brain. Each NIFTI file contains a segmented mask that is mapped to a region of the brain to indicate the Hippocampal area of the brain. The convolutional neural net will be trained on this data to recognise the Hippocampus. 

![Tensorboard](./Screenshot/Tensorboard.jpg)

# How the Training Data has been Labelled:

The labels have been created and verified by radiologists who are experts in their field. Therefore, the labelled datasets are reliable and accurate.   

# Training Performance:

The training will be according to the Dice and Jaccard scores. These evaluation metrics are commonly used in image segmentation tasks to evaluate the performance of the comolutional neural network. The Dice and Jaccard metrics are used to measure the overlap of the groundtruth and prediction data. 

# How Well the Algorithm Performance:

Based on the Dice and Jaccard metrics, the scores were x and x respectively. The algorithm was able to provide a volume that is expected and within range of previous scores - between 2200 and 4500 mm^3. For the purposes of this project, this is a good enough level of performance based on the Jaccard, Dice and volumetric scores as the final respective metric is within range.  

![Report](./Screenshots/Report.jpg)
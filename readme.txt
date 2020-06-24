The following are the directories for the project:

1.) bounding_box - It contains the manual annotation XML files of 9 plant disease classes (manually annotated).

2.) code - It contains 6 jupyter notebook files (using PyTorch)
	-data_split.ipynb - The code that is used to split the color dataset and segment image dataset into 3 splits: train (60% of the whole dataset), test(20% of the whole dataset), 				   validation (20% of the whole dataset)
	-proj_classification.ipynb - AlexNet and ResNet (color and grayscale) implementation along with visualization of intermediate layers in AlexNet model.
	-proj_classificationNew.ipynb - AlexNet and ResNet (segmented images).
	-proj-classification-densenet.ipynb - DenseNet implementation (color, grayscale and segmented) implementation.
	-proj-classification-fromScratch.ipynb - Trained a model from scratch (color, segmented and grayscale) implementation.
	-proj-grid.ipynb - It contains the code for the prediction of the bounding boxes using ResNet18 model.

3.) color - It contains the sub-directory named "60_20_20" which in turn contains 3 sub folders: train, test and validate. Each folder has the corresponding files split using data_split.ipynb.
	-60_20_20
		-train
		-test
		-validate

4.) leafDataForBoudingBox - It contains the 9 subfolders corresponding to 9 classes (original color images) that are manually annotated (with bounding boxes).

5.) segment - It contains the segmented images of the original dataset. It consists of 38 class folders.

Execution of the code:

Please run the jupyter notebook files present in the code folder for your reference. (The path settings are already intact). 






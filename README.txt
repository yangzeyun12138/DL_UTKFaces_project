README

ECE 685D Intro To Deep Learning
Final Project (Porject Number: S1)
Date 11/30/2022

Done by Zeyun Yang (netID: zy139)
	Yesen Chen (netID: yc507)

The code of the project contains these parts:
	
	The project has 2 folders in it: Faces and checkpoint
	Faces has a "UTKFace" folder within, which contains all the images of human faces ready for training
	checkpoint contains the historis, models, and results of our training, and the text file within each folder within are 
	the traing outcomes
	Note: Due to the size of UTKFace folder is too large to submit, please download the UTKFace dataset folder from
	https://www.kaggle.com/datasets/jangedoo/utkface-new, and substitute the empty UTKFace here.
	 

	The project has 2 ipynb files: final_project.ipynb and main.ipynb.
	The final_project.ipynb file provides visualizations for our datasets. Run all of it to visualized the dataset of UTKFaces, 
	including mean, standard distribution, and etc. Dependent on UTKFace.
	The main.ipynb impelements the resnet, LDS, and FDS algorithms, trains and tests the datasets for our desired results and losses.
	Depend on UTKFace, and all .py files below.
	All the necessary external dependency moduels are imported at the top blocks in these two ipynb files, please install them to 
	run the code.

	The project has 5 .py files, which are datasets.py, fds.py, loss.py, resnet.py, and utils.py.
	These are most fundemental modules that realize the training and testing of the neural network.

The report of the project is the pdf file in this folder.

The General Structure is like this:

	P_S1_g2 ---- final_project.ipynb 
		|--- main.ipynb
		|--- datasets.py
		|--- fds.py
		|--- loss.py
		|--- resnet.py
		|--- utils.py
		|--- Faces ---- UTKFace ---- images.png
		|--- checkpoint---- agedb_resnet50_adam_l1_0.001_64
				|-- agedb_resnet50_fds_gau_9_1_0_1_0.9_adam_l1_0.001_64
				|-- agedb_resnet50_lds_gau_9_1_adam_l1_0.001_64

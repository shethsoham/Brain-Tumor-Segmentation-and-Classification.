Dataset Download Link:
https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation

The zip contains the following files:
1) Brain_Tumor_Segmentation_unet_notebook.ipynb - This is the notebook file.
2) Brain_Tumor_Segmentation_unet.py
3) U-Net with Attention Architecture.png - UNet architecture with attention
4) U-Net without Attention Architecture.png - UNet architecture without attention
5) (1)Unet model with attention.mp4 - Executable video for u-net model with attention
6) (2)Unet model without attention.mp4 - Executable video for u-net model without attention
7) configurations.txt - the file that contains the configuration of the local system on which the program was run.
8) Prediction Results with Unet model with attention - Folder containing results
9) Prediction Results with Unet model without attention - Folder containing results

How to run the notebook:
A]
1) Install Anaconda from https://www.anaconda.com/
2) Install Python 3.x (https://www.python.org/downloads/)
3) Launch Jupyter in GPU kernel

B]
1) Open Google Colaboratory
2) Select GPU runtime from option Runtime -> Change runtime type

How to run the .py file: (Need graphics driver like NVIDIA and libraries like cuda and then we can configure in python path in vscode)
1) Any editor for python file e.g. VS Code.
2) Install Python 3.x (https://www.python.org/downloads/)
3) Install all the needed dependencies from the requirements.txt file using:
	pip install -r requirements.txt

# VQA Demo
This directory contains a demo code for the Lightweight VQA repository. This demo is dependent from Google Colab's libraries. Unless there is way to import these libraries into a local notebook, the demo must be done one Colab.
# How to run the demo
To run the demo follow these steps : 
1. run `Install_demo.ipynb` : This notebook settles the needed file hierarchy and install the necessary data. You must specify the `demo_root` variable.
2. run `demo.ipynb` : You must first initialize `demo_root` with the same value given to `demo_root` in `Install_demo.ipynb` When you run this notebook, it will give you the ability enter one of the following commands :
	* up_im : upload an image
	* up_vid : upload a video then click on the video to get the current image.
	* last_vid : get the last video uploaded (not to re-upload the video).
	* live : activate the pc front camera and then click on the video to get the current image.
	* stop : stop the process

	Once you get the image, you can instead of giving a command ask a question about the image. If you want to change the current image, just enter a command instead of a question. The questions are not case sensitive and don't need question marks. The image must have `.jpg` extension.
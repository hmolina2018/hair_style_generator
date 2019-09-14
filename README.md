# hair_style_generator
This is a Pix2Pix implementation that tries to generate a haircut based on a drawing
## Purpose
Just have fun using a machine learning algorithm to solve a trivial problem
## Setup
 1. Import the notebook into Google Collab.
 2. Create the following folders in your Google Drive:
	- /content/drive/My Drive/pix2pix/jmamoon/hairstyle_filtered/input
	- /content/drive/My Drive/pix2pix/jmamoon/hairstyle_filtered/output
	- /content/drive/My
   Drive/pix2pix/jmamoon/hairstyle_filtered/generated_training
	- /content/drive/My
   Drive/pix2pix/jmamoon/hairstyle_filtered/generated_testing
	- /content/drive/My
   Drive/pix2pix/jmamoon/hairstyle_filtered/checkpoints
3. Import the dataset from https://drive.google.com/drive/folders/13eFWEYs-onnpE__gZkTXz-IeEcJzwMJG
4. Run the notebook 
## About the dataset
I used the Figaro 1k dataset to generate the input and output images. You can see more information about Figaro 1k in [http://projects.i-ctm.eu/en/project/figaro-1k](http://projects.i-ctm.eu/en/project/figaro-1k)
## Problems I faced
Dataset had too much variety I needed to filter to improve generation, but it reduced my dataset amount, so, I think it reduced the data quality.
## What I've learned
Dataset determines how good is your neuronal network going to work.
## Conclusion
Results were not as good as I expected, but I think It can be improved by adding more images in the dataset and preparing the input images in a better way.

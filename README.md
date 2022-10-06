# CARE/Stardist tutorials for EMBO Practical Course — Computational optical biology 2022

### Setup 

1. Clone this repo:

  `git clone https://github.com/maweigert/embo_2022.git`

2. Install the conda environment 

  `conda env create -f environment.yaml`


3. Activate environment and start jupyter

  ```
  conda activate stardist
  jupyter notebook
  ```


### Tutorials 

In the two subfolder, there are two workflows for CARE (image restoration) and stardist (2D or 3D) that you an both try. 

* Task 1: CARE workflow for restoration of noisy and downsampled images. Find the notebook(s) in subfolder `care`.
* Task 2: stardist workflow in 2D for segmentation of nuclei. Find the notebook(s) in subfolder `stardist` (choose the 2D one).
* Task 2b: Stardist Colab:  https://colab.research.google.com/github/maweigert/stardist-i2k/blob/main/notebooks/stardist_example_2D_colab.ipynb
* Task 3: Apply the trained stardist model to a test image via anapri and the stardist plugin.






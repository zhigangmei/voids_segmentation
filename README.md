# voids_segmentation

Semantic segmentation of voids in irradiated materials using pytorch models

## Download `voids_segmentation` model 

Get the latest version using git to "clone" a local copy of the GitHub repository on your computer: `git clone https://github.com/zhigangmei/voids_segmentation.git`.
The cloning process will download the source code to your system to a new folder (named `voids_segmentation`) that contains the configuration files needed to keep the folder up to date with GitHub. 
In the future, you can get the latest copy of the software by calling `git pull` from inside the `voids_segmentation` folder.

## Installation

Build the environment by calling `conda env create --file environment.yml` from the command line.
Anaconda will then create a new environment, named "voids_segmentation" which you must activate before working with your tools.

Add `cudatoolkit` dependency in environment.yml to enable Pytorch running on GPU.

## Use

1. Activate conda environment: ``conda activate voids_segmentation``
2. Change directory to ``voids_segmentation``
3. Copy the pre-triained model ``voids_segmentation_091321.pth`` (shared in Box) to the same folder
4. Launch Jupyterlab: `jupyter lab`
5. Open jupyter-notebook: `Voids_prediction_pytorch.ipynb`
6. Test model on your own images: copy images to the `test_images` folder 


## Support

This material is based upon work supported by Laboratory Directed Research and Development (LDRD) funding from Argonne National Laboratory, provided by the Director, Office of Science, of the U.S. Department of Energy under Contract No. DE-AC02-06CH11357.

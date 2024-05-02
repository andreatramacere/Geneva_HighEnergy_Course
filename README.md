# Geneva JetSeT Hands-on Session

## git repo with notebooks 

- to get the notebooks:
  `git clone https://github.com/andreatramacere/Geneva_HighEnergy_Course`

OR if you don't have git installed on your machine

- download visiting <https://github.com/andreatramacere/Geneva_HighEnergy_Course>

You can access/download the slides directly here: https://github.com/andreatramacere/Geneva_HighEnergy_Course/blob/main/Geneva_HighEnergy_Course_slides.pdf

## Instructions for the hands-on session:

### Requirements
We will work with version 1.2.2. There binaries are distributed only for **linux** and **MacOS(X86 architecture)**, 

 - If you have a **Mac with ARM architecture (M1/2/3)**, and you system is not able to install the X86 version,
 please contact me to install from source, or to install the binaries of version 1.3.0.  I will setup a Zoom call to guide you during the installation 

 - for **Windows** users, please install WSL: https://learn.microsoft.com/en-us/windows/wsl/install

 - in case of impossibility to run the code on your laptop, you can run the notebooks on a remote binder server (see next section)


### Running the notebooks 

you can run all the notebooks locally on your laptop (Method 1) **or**  on a remote server (Method 2)



- Method 1) Run the notebooks on your laptop: 
    
    The easiest solution is to create a conda environment

  - install anaconda from: https://www.anaconda.com/download/ 

    *OR*   
 
  - it will work also with mamba if you prefer: https://mamba.readthedocs.io/en/latest/index.html, just replace `conda`   with `mamba` in the following steps
  
  - create the virtual environment:  `conda create --name jetset python=3.9 ipython jupyter`

  - activate the environment: `conda activate jetset`
  
  - install the code `conda install -c andreatramacere -c astropy -c conda-forge 'jetset>=1.2'`

  - run the notebooks using `jupyter-notebook` or any IDE (e.g. VScode) with a jupyter notebook plugin

- Method 2) Run the notebooks on binder (remote server): 
 
  - run the notebooks using this link [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andreatramacere/Geneva_HighEnergy_Course/HEAD)


The JetSeT documentation is here: https://jetset.readthedocs.io/en/stable/index.html




## To updated on the jestet
- keep updated on the FB page <https://www.facebook.com/jetsetastro/>
- subscribe to the git repository: https://github.com/andreatramacere/jetset

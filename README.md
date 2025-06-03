A fresh install of Micromamba over a default install of Anaconda/Miniconda is encouraged. 
Instructions [here] (https://www.anaconda.com/docs/getting-started/miniconda/install#quickstart-install-instructions)

On Linux:
1. Clone this directory: `git clone https://github.com/eleR09173/PTA_NESSAI-ENV.git`
2. Enter the cloned directory: `cd PTA_NESSAI-ENV`
3. Install the environment: `micromamba env create -f anaconda-env.yml`
5. Activate the environment: `micromamba activate IPTA_Env_nessai`

On MacOS with Arm64 architecture:
1: Clone this directory: `git clone https://github.com/eleR09173/PTA_NESSAI-ENV.git`
2: Enter the cloned directory: `cd PTA_NESSAI-ENV`
5: Install the environment:  `micromamba env create --platform osx-64 --file anaconda-env.yml`
6: Activate the environment: `micromamba activate IPTA_Env_nessai`


Dockerfile is needed to run the PTA_NESSAI repo on Mac

Singularity is to run on clusters

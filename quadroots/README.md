## Synopsis
A collab with [Sergey Saveliev](https://scholar.google.com/citations?user=6eXz_IIAAAAJ&hl=en&oi=ao) and [Luke De Clerk](https://www.lboro.ac.uk/departments/physics/pg-research/phd/students/luke-de-clerk/). Playing with quadratic equation coefficient and root prediction.

## Installation
#### Requirements:
* OS: Linux machine or [WSL2](https://docs.microsoft.com/en-us/windows/wsl/install-win10) on Windows.
* Preferable to have a modern Nvidia GPU, although not required (will fall back on CPU but will be slower).
* Install `conda` package/environment manager, here: [Miniconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html#install-linux-silent). Read `conda` [getting started](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html) if not familiar.

#### Setting up the environment:
From within this `quadroots/` directory run commands:
```bash
conda env create --file environment.yml -y
conda activate py38_quadroots
```
This will install all the required Python packages in a separate environment `py38_quadroots`.

#### Running the code:
From within this `quadroots/` directory run command:
```bash
jupyter-lab
```
Then navigate in your browser to the URL that is printed in the console to access Jupyter Lab (if not familiar, see [getting started](https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html)). Open and run `quad.ipynb`.
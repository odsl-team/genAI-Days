# GenAI-Days

Welcome to the ODSL GenAI-Days!

In this three-day workshop, we will cover
1. Normalizing Flows (by [Annalena Kofler](https://www.annalenakofler.com))
2. Flow Matching (by Nicole Hartman)
3. Diffusion Models (by Eva Sextl)
and their application to physics.

To run the tutorials, download this repository with 
```
git clone [https or ssh link]
```
create a new virtual environment via
```
python -m venv venv-genai
```
and activate it with
```
source venv-genai/bin/activate
```

Afterwards, enter the `genAI-Days` folder with `cd genAI-Days` and install all requirements via
```
pip install -r requirements.txt
```

If you want to use `conda` to setup the environment (or you have problems installing [`lalsuite`](https://wiki.ligo.org/Computing/LALSuiteInstall)), you can use the following commands:
```
conda create -c conda-forge -n genai python=3.10 pytorch lalsuite glasflow corner numpy matplotlib jupyter tqdm
conda activate genai
```

You can start the jupyter notebook by typing `jupyter notebook` in the terminal. 


**Data generation:**

The data is generated in the nb:
- `01_normalizing_flows/01_data_generation.ipynb`

Also on **dropbox** [here](https://www.dropbox.com/home/ODSL-genAIdays-data)

`**Open in colab:**

To open these notebooks in collab, use the link below:


[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/odsl-team/genAI-Days/blob/main/)

For running in collab generating the data in one notebook and then loading it in the other notebook, just need to make sure you save the data to your google drive and then load it back in.

To have access to your google drive on (?) you first need to mount it:

```
from google.colab import drive
drive.mount('/content/drive')
```

And then set `data_folder` to your corresponding drive.

`data_folder = "/content/drive/My Drive”`

There are also a few packages that aren't previously installed in the default collab interface, but you can install them in a dedicated cell before the import, e.g, 

`!pip install lalsuite`

`!pip install corner`

and so on :)

Happy coding!!

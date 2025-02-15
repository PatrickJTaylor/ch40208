# Getting started with Jupyter Notebooks

## First Time Logging On to the JupyterHub Server

When you first log on to the [JupyterHub server](./how_to_access_the_jupyterhub_server.md) you should see a screen like this:

![](https://github.com/pythoninchemistry/ch40208/raw/master/CH40208/notebooks_introduction/images/jupyter_hub.png)

This is the **Notebook Dashboard**, which allows you to access and manage your Jupyter Notebooks. The Dashboard allows you to create, open, rename, move, and delete Notebooks.

If you have just logged onto the JupyterHub server for the first time, You may have two items already listed in your Dashboard:
- A folder named `courses`.
- A Notebook named `Welcome.ipynb`.

If you do not have these files, **don't worry** we won't be using these in the course. 
  
## Creating a new Jupyter Notebook

To create a new Notebook, click on `New` on the right-hand side of the screen, and then select `Python 3` from the drop-down menu:

<p align="center">
  <img src="https://github.com/pythoninchemistry/ch40208/raw/master/CH40208/notebooks_introduction/images/new.png" width="25%" />
</p>

This will open a brand new Notebook called `Untitled.ipynb`:
The `.ipynb` file extension indicates that `Untitled.ipynb` is a Jupyter notebook.

![A freshly created Notebook](https://github.com/pythoninchemistry/ch40208/raw/master/CH40208/notebooks_introduction/images/untitled.png)

## Renaming a Notebook

Naming your notebook`Untitled.ipynb`, or worse `Untitled37.ipynb`, is not very informative, and can be a problem when you come back to a project and need to find __just the right__ piece of data analysis. It is a good idea to give your Notebook a more meaningful name as soon as you create it.

![](https://github.com/pythoninchemistry/ch40208/raw/master/CH40208/notebooks_introduction/images/renaming.png)
<p align="center">Don't be this person.</p>

To rename your Notebook, you can either click on `File` -> `Rename…`:

![](https://github.com/pythoninchemistry/ch40208/raw/master/CH40208/notebooks_introduction/images/f_rename.png)

Or click directly on the Notebook name (currently &ldquo;Untitled&rdquo;) at the top of the screen. Either way opens a `Rename Notebook` popup:

![](https://github.com/pythoninchemistry/ch40208/raw/master/CH40208/notebooks_introduction/images/popup.png)

To rename your Notebook, type in a new name and click `Rename`. (Go on, try it).

If you close the tab that contains your notebook you might notice something unexpected:

![](https://github.com/pythoninchemistry/ch40208/raw/master/CH40208/notebooks_introduction/images/unexpected.png)

The notebook icon next to your notebook is now green, and on the right side you can see `Running`. We will explain what it means to have a Notebook "running" later. For the moment you can stop this Notebook running by selecting the checkbox to the left of the Notebook icon, and clicking `Shutdown` in the menubar above the list of files and folders.

<p align="center">
  <img src="https://github.com/pythoninchemistry/ch40208/raw/master/CH40208/notebooks_introduction/images/shutdown.png" width="25%" />
</p>


## Duplicating a Notebook

To duplicate your notebook, you can **make a copy** by selecting `File` -> `Make a Copy…`

![](https://github.com/pythoninchemistry/ch40208/raw/master/CH40208/notebooks_introduction/images/duplicate.png)

This opens another browser tab with your copied Notebook running in it. Your copy will have the same name as the original Notebook, but with `-Copy1` appended to the title (or `-Copy2` etc. if you have already created one copy).

Making a copy if useful if you want to make changes to a Notebook but you want to still be able to refer back to the original Notebook, or you might want a second Notebook that is similar to a Notebook you have already written, and you don't want to start from scratch; for example, if you are analysing data from a series of experiments and have created a notebook to run the analysis on one experiment, you might duplicate (copy) and then make minor changes to analyse the other experiments.

Just as it is bad practice to leave notebooks called `Untitled.ipynb` sitting around, you probably want to rename your duplicated notebook at the time of creation, instead of later wondering what the difference is between `Analysis.ipynb` and `Analysis-Copy3.ipynb`.


# si313_w26
SI 313 Introduction to Quantitative Methods

Offered through the University of Michigan School of Information (UMSI) during Winter term 2026

This course provides a foundational understanding of quantitative research methods. Students will learn how to collect, analyze, and interpret quantitative data. The course emphasizes practical application through hands-on exercises and projects. Topics include basic statistics, probability, data collection, and interpretation. Students will practice collecting and analyzing data using Python and Jupyter Notebooks.

## Last Updated Notes

Updated on Feb 4, 2026
- Added template for Readymade Data Module assignment
- Added a tutorial for using `pandas` to read, clean and manipulate data in `/lecture_notebooks` folder.

## How to use this repo

This repo contains the lecture notes, class demo notebooks, and the assignment templates. You can clone this repo to your local machine and then copy the files into another folder. You **cannot** commit or push any changes to this repo. 

Before each class, you can pull the latest changes from this repo to your local machine using: `git pull`. If you have local conflicts, you can resolve them by hand or use `git reset --hard origin/main`. But be careful, this will overwrite any changes you have made to files within this folder.

## Setup your environment

### Install packages

These are the packages we will be using mostly in this course: `numpy pandas matplotlib seaborn scipy statsmodels scikit-learn`. You can install them using `pip` or `conda`, like in a code cell in you notebook, run
```python
!pip install numpy pandas matplotlib seaborn scipy statsmodels scikit-learn
```

### VS Code

#### Virtual Environments
Think of a _virtual environment_ as an isolated container for each of your Python projects. It ensures that the specific tools and libraries one project needs don't interfere with or break another project on your computer.

[Here's a video with info about using virtual environments in VS Code](https://www.youtube.com/watch?v=D2cwvpJSBX4).

Best practice is to have one virtual environment for each project. If 313 assignments are the only Python you're working on, you could use your "base" Python. You used Anaconda in 201, and it is a tool for managing virtual environments. Anaconda manages environments through its own package manager called `conda`.

### Google Colab

If managing local Python environments isn't working, or you just don't want to, you can also use Google Colab in your VS Code or in your browser. Google Colab is a cloud-based environment that allows you to run Python code at server at no cost (except you have needs to use GPU or other high-performance resources). Here's a general workflow to set up `colab` kernel:

#### Colab in VS Code 
1. Install the [`colab` extension](https://marketplace.visualstudio.com/items?itemName=google.colab) in VS Code
2. Open up any Jupyter notebook in your VS Code -> Select Kernel -> Select Another Kernel -> Select Colab -> Auto Connect
3. Now it will pop up a new window in your browser and ask you to sign in with your any google accounts. -> Login with your google account
4. Return to your VS Code -> Select Python3 Kernel
5. Test with some import statements like `import pandas as pd` to make sure it works.

You can also work in your browser with Google Colab. Here's a general workflow:
1. Open [Google Colab](https://colab.research.google.com/) in your web browser
2. Choose File → Open notebook → GitHub → (enter this GitHub repo's address) → choose the assignment template you want to work on
3. Choose File → Save a copy in Drive (or Save a copy in GitHub) 
4. Complete the assignment *in that copy* on Colab
5. Choose File → Download → Download .ipynb
7. Upload the .ipynb you downloaded to the relevant Canvas assignment and submit

Something you need to know about Google Colab:
1. Google Colab cannot directly read your local files. When you are working on an assignment using `colab` kernel in VS Code, you need to upload the file to Google Colab first. Make sure you have permission to upload the data before you do.
2. If you are using U-M account to use Google Colab, please note that Colab use is not covered under the U-M's Google Workspace agreement. This means U-M does not provide support for it. Please see [U-M ITS Page](https://teamdynamix.umich.edu/TDClient/30/Portal/KB/ArticleDet?ID=7289)


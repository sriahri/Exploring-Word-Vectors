# Exploring-Word-Vectors
Word Vectors are often used as a fundamental component for downstream NLP tasks, e.g. question answering, text generation, translation, etc., so it is important to build some intuitions as to their strengths and weaknesses. Here, you will explore two types of word vectors: those derived from co-occurrence matrices, and those derived via GloVe.

But make sure that it is at least Python version 3.5. If not, the easiest thing to do is to make sure you have at least 3GB free on your computer and then to head over to (https://www.anaconda.com/download/) and install the Python 3 version of Anaconda. It will work on any operating system.

After you have installed conda, close any open terminals you might have. Then open a new terminal and run the following command:

# 1. Create an environment with dependencies specified in env.yml:
    
    conda env create -f env.yml

# 2. Activate the new environment:
    
    conda activate csci5800
    
# 3. Inside the new environment, install IPython kernel so we can use this environment in jupyter notebook: 
    
    python -m ipykernel install --user --name csci5800


# 4. Assignment1 is a Jupyter Notebook. With the above done you should be able to get underway by typing:

    jupyter notebook Assignment1_CSCI5800.ipynb
    
# 5. To make sure we are using the right environment, go to the toolbar of Assignment1_CSCI5800.ipynb, click on Kernel -> Change kernel, you should see and select csci5800 in the drop-down menu.

# To deactivate an active environment, use
    
    conda deactivate

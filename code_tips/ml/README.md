# Creating a Machine Learning environment in Windows 10 64-bit PC

1. Install latest Miniconda
   - [https://docs.conda.io/projects/miniconda/en/latest/index.html](https://docs.conda.io/projects/miniconda/en/latest/index.html). Older versions of Miniconda is available at [https://repo.anaconda.com/miniconda/](https://repo.anaconda.com/miniconda/)
2. Install Miniconda using default settings
3. Create a New folder in the Drive
   - Open `Windows 10` command prompt, `cmd`
   - Change the drive to E: (or any other drive than C:)
   - Create New Folder named `ml` in the current drive (E: drive)
     ```
     mkdir ml
     exit
     ```
4. Create a Machine Learning environment inside the New folder created in the drive
   - Open the `Anaconda` command prompt
   - Navigate to the New Folder created
     ```
     E:
     cd ml
     ```
   - Create the `conda` environment in `ml` folder in `Anaconda` command prompt
     ```
     conda create --prefix ./env pandas numpy scikit-learn tensorflow tensorflow-hub
     conda install --prefix ./env jupyter
     ```
   - Verifying the successful creation of `conda` environment in `Anaconda` command prompt
     ```
     conda env list
     ```
   - Activating `conda` environment for Machine learning programming/coding in `Anaconda` command prompt
     ```
     conda activate E:\ml\env
     ```
   - Opening Jupyter Notebook in the `conda` environment in the `ml` folder in `Anaconda` command prompt
     ```
     jupyter notebook
     ```
     The default browser will open with the jupyter notebook
5. Open the new notebook for python 3 programming/Machine learning programming 

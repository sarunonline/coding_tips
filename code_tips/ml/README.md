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
   - Open `Anaconda` command prompt
   - Navigate to the New Folder created
     ```
     E:
     cd ml
     ```
   - Create the Conda environment in `ml` folder

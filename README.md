# Graph Machine Learning
## May 2023


<br><br>


### Cloud Machine : Google Colab (Free GPU)

* Follow this Notebook installation :<br>
https://colab.research.google.com/github/xbtrainings/GML_May23/blob/master/codes/installation/installation.ipynb

* Open your Google Drive :<br>
https://www.google.com/drive

* Open in Google Drive Folder 'GML_May23' and go to Folder 'GML_May23/codes/'<br>
Select the notebook 'file.ipynb' and open it with Google Colab using Control Click + Open With Colaboratory



<br><br>

### Local Installation for OSX & Linux

* Open a Terminal and type


```sh
   # Conda installation
   curl https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh -o miniconda.sh -J -L -k # Linux
   curl https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh -o miniconda.sh -J -L -k # OSX
   chmod +x miniconda.sh
   ./miniconda.sh
   source ~/.bashrc

   # Clone GitHub repo
   git clone https://github.com/xbtrainings/GML_May23.git
   cd GML_May23

   # Install python libraries
   conda env create -f environment.yml
   source activate gnn_course

   # Run the notebooks in Chrome
   jupyter notebook
   ```




### Local Installation for Windows 

```sh
   # Install Anaconda 
   https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe

   # Open an Anaconda Terminal 
   Go to Application => Anaconda3 => Anaconda Prompt 

   # Install git : Type in terminal
   conda install git 

   # Clone GitHub repo
   git clone https://github.com/xbtrainings/GML_May23.git
   cd GML_May23

   # Install python libraries
   conda env create -f environment.yml
   conda activate gnn_course

   # Run the notebooks in Chrome
   jupyter notebook
   ```

   
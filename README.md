# Predictive Toxicology
Scripts and data to compare the influence of different sampling methods on predictive toxicology using Random Forests and Deep Neural Networks (DNN). 

Publication: https://www.frontiersin.org/articles/10.3389/fchem.2018.00362/full

# Installation
To run the Scripts, a recent version of python 3 is needed. Linux and macOS normaly have python already installed.
- Installation guide: https://realpython.com/installing-python/.

If you want to use a IDE I recommend PyCharm: [https://docs.spyder-ide.org/current/installation.html ](https://www.jetbrains.com/de-de/pycharm/) (Video: https://www.youtube.com/watch?v=56bPIGf4us0)
## python packages
Multiple python packages are needed to execute the scripts. To install python packages use 'pip install \<package\>' in the terminal/cmd/powershell. E.g. 'pip install numpy'
- numpy
- pandas
- rdkit
- joblib
- sklearn
- openpyxl
- matplotlib
- tkinter
- tensorflow
## Run the Script
To run the script, just download the repository as .zip, unzip it and run 'submitScriptOrig.py' either by typing 'python3 submitScriptOrig.py' in your terminal/cmd/powershell or by klicking on 'Run file' in Spyder. The algorithm creates multiple output directorys with sampled data, result tabels and plots.

Different sampling methods can be tested by changing the sampling variable in 'submitScriptOrig.py' (line 69). Default sampling method is kMedoids2. 

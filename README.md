# Anaconda

https://conda.io/projects/conda/en/latest/user-guide/getting-started.html

## 1. check conda version

conda --version

## 2. update conda

conda update conda

## 3. create new conda environment

conda create --name [environment name] python=[python version such as 3.9] [packages]

if failed, try this code before the creation: conda config --set ssl_verify false

## 4. activate new environement

conda activate [environment name]

## 5. To see a list of all your environments

conda info --envs

## 6. Change your current environment back to the default (base)

conda activate

## 7. Verify which version of Python is in your current environment:

python --version

## 8. Check to see if a package you have not installed is available from the Anaconda repository (must be connected to the Internet):

conda search [package name]

## 9. Install package into the current environment:

conda install [package name]

## 10. Check installed packages

conda list

## 11. remove conda environment

conda env remove -n [environment name]

# VS code 

https://code.visualstudio.com/docs

## 1. virtual environment 

https://code.visualstudio.com/docs/python/environments

https://www.roelpeters.be/virtualenv-venv-choose-python-version/

python -m venv [environment name]

## 2. Select Interpreter

Python: Select Interpreter (ctrl+shift+P)

## 3. Version Controlling with Git in Visual Studio Code and Azure DevOps

https://www.azuredevopslabs.com/labs/azuredevops/git/#task-2-reviewing-commits

## 4. install the packages in requirements.txt file

conda install --file requirements.txt

pip install -r requirements.txt

## 5. NLTK install

 python -m nltk.downloader -d nltk_data punkt stopwords wordnet maxent_ne_chunker words averaged_perceptron_tagger

## 6. install packages with specified version

pip install -Iv MySQL_python==1.2.2

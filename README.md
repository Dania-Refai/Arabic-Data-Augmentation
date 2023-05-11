# Arabic-Data-Augmentation
> #### Author: Dania S. Refai
> #### Date: 10/05/2023


> #### Make sure you have pytorch installed on your machine. Moreover, if you want more information please refer to INSTALL PYTORCH [https://pytorch.org/] from their official website.
> #### Make sure your installed python version is 3.8
> #### Make sure you are running the commands INSIDE source code directory (.\Implementation\)
> #### Create and activate a Virtualenv (Windows based systems)
    set PATH=C:\Users\<<username>>\AppData\Local\Programs\Python\Python38\
    %PATH%\python.exe -m pip install --upgrade pip
    %PATH%python.exe %PATH%Scripts\pip.exe install virtualenv    
    %PATH%\python.exe -m virtualenv venv 
    
> #### Activate the virtual environment:
    .\venv\Scripts\activate

> #### Install requirements:
    .\venv\Scripts\pip3 install python-dotenv
    .\venv\Scripts\pip3 install -r requirements.txt


> #### LINUX 
    python3 -m pip install --upgrade pip
    python3 -m pip install virtualenv
    python3 -m venv myenv 
    source  ./venv/bin/activate
    python3 -m pip install psycopg-binary
    python3 -m pip install python-dotenv
    python3 -m pip install -r requirements.txt

> #### Paper Implementation:
The implementation of the approach is all located in the jupyter notebooks:
* '_TG': for original dataset generation using transformers.
* '_DA': for data augmentation of each dataset.
* '_SA': for sentiment analysis of each dataset.
* '_PR_ROC': for investigating the PR/ROC of each dataset.

> ### Citation:
please, if you use any of the resources listed in this repo. to use the following citation for the published paper:
{{CITATION}}









### Using this Repository:
1. Setup your virtual environment
```angular2html
$ conda env create -f environment.yml
$ conda activate cs7643
$ pip install -r requirements.txt
```
NOTE: If you are working on a separate branch and make any additional pip installations, be sure to **update the `requirements.txt` file**. 

2. [Sync your Jupyter Kernel up with your environment](https://janakiev.com/blog/jupyter-virtual-envs/)
```angular2html
$ pip install ipykernel
$ python -m ipykernel install --user --name=cs7643
```
3. Launch Jupyter Notebook
```angular2html
$ jupyter notebook
```

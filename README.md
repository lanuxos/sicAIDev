# Samsung Innovation Campus - AI Developer

## environment set up
- install miniconda
### coding programming and data science
- create environment
- install ipykernel
- install jupyter notebook
```shell
conda create --name SIClab
activate SIClab
conda install ipykernel
python -m ipykernel install --user --name SIClab --display-name "SIClab"
conda install jupyter
jupyter notebook
```
### AI developer
- create environment
- install ipykernel
- install jupyter notebook
- install tensorflow
- [test](http://localhost:6006/)
```shell
conda create --name AI-Dev python=3.11.11
activate AI-Dev
conda install ipykernel
python -m ipykernel install --user --name AI-Dev --display-name "AI-Dev"
conda install jupyter
pip install tensorflow==2.19.0
tensorboard --logdir=logs/
```

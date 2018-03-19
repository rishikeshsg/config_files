```
jupyter notebook --generate-config
```
```
vi .jupyter/jupyter_notebook_config.py
```
Append at end

```
c.NotebookApp.ip = '*'
c.NotebookApp.password = u'sha1:enter sha key here'
c.NotebookApp.open_browser = False
c.NotebookApp.port = 8888
```

_______________

https://github.com/ipython-contrib/jupyter_contrib_nbextensions

```
pip install --user jupyter_contrib_nbextensions
```  
**OR**  
```
conda install -c conda-forge jupyter_contrib_nbextensions
```  

```
jupyter contrib nbextension install --user
```
_________________
https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator

```
pip install --user jupyter_nbextensions_configurator
```
```
jupyter nbextensions_configurator enable --user
```
**OR**
```
conda install -c conda-forge jupyter_nbextensions_configurator
```


# Deep Learning Notebooks (dl-notebooks)

- hello-jupyter
- hello-camera (OpenCV)

Note,
- Use jupyter Termial to install 'opencv-python'
```
pip install opencv-python
```

## Adding the R to Jupyter Notebook
```
conda install -c r r-irkernel
```

## Using SSL
```
openssl req -x509 -nodes -days 3650 -newkey rsa:2048 -keyout jupyter.key -out jupyter_cert.pem
jupyter notebook --ip 172.17.4.121 --certfile=jupyter_cert.pem  --keyfile=jupyter.key
```

## Reference
https://github.com/PacktPublishing/Jupyter-Cookbook/tree/master

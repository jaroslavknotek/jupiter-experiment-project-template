# jupiter-experiment-projet-template

The name for the environment is `expjup`. You should change it to your own `<env-name>`

```
sed -i s/expjup/<env-name>/g environment.yml *.ipynb
```

Install conda environment and activate it
```
conda env create -f environment.yml
conda activate <env-name>
```


Then run this to add env to kernel
```
python -m ipykernel install --user --name=<env-name>
```

Inspired by [this](https://towardsdatascience.com/structuring-jupyter-notebooks-for-fast-and-iterative-machine-learning-experiments-e09b56fa26bb)
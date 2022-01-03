# jupiter-experiment-projet-template

The name for the environment is `expjup`. You should change it to your own `<env-name>`

```
sed -i s/expjup/<env-name>/g environment.yml *.ipynb
```

Then run this to add env to kernel
```
python -m ipykernel install --user --name=<env-name>
```
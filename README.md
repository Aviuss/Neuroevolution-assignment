# Neuroevolution-assignment

# Instructions for running it

```
python3.11 -m venv venv
source venv/bin/activate

pip install jupyter ipykernel neat-python graphviz matplotlib numpy scikit-learn tqdm gymnasium "gymnasium[classic-control]" swig "gymnasium[box2d]"

python -m ipykernel install --user --name=venv
```

And then open `main.ipynb` to run the notebook.
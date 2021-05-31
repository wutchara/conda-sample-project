# conda-sample-project

---

- Install miniconda
```bash
conda create --prefix ./env pandas numpy matplotlib scikit-learn jupyter

conda activate {{PATH}}

# If already not use
conda deactivate
```

---

Share project
```bash
conda env export --prefix C:\Users\wutchara\Downloads\sample_project\env > environment.yml
```

Create proect with sharing
```bash
conda env create --file environment.yml --name env_from_file
```

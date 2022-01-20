# ANTsPy_container
A Singularity container that tracks the latest version on GitHub

# Building
```
sudo singularity build antspy.sif ANTsPy.def
```

# Running
Assuming your code is in a local `code/` folder and your data is in `data/`.
```
singularity run -B code:/code -B data:/data antspy.sif  /code/run.py
```

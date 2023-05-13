# Conda environment with environment.yml

[![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/binder-examples/conda_environment/HEAD?filepath=index.ipynb)

A Binder-compatible repo with an `environment.yml` file.

Access this Binder by clicking the blue badge above or at the following URL:

http://mybinder.org/v2/gh/binder-examples/conda_environment/HEAD?filepath=index.ipynb

## Notes

This is my first excercise using markdown language and understanding the principles of it. So far I have learned that `mark_` marks the code; for
example if I would like to distinguish that a word copy is part of the code I would write it `copy`.

The number sign is used for headings and the amount of number signs defines the level of heading. For title the number is one, for sub-titles two and for sub-sub-titles three. So, for creating a new sub-title I would use marking:

## Example heading

The `environment.yml` file should list all Python libraries on which your notebooks
depend, specified as though they were created using the following `conda` commands:

```
conda activate example-environment
conda env export --from-history -f environment.yml
```

Note that the only libraries available to you will be the ones specified in
the `environment.yml`, so be sure to include everything that you need! 


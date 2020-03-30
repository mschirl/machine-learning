# Machine Learning Exercises


This repository created by [Reuf Kozlica](https://github.com/reufko) and [Max Schirl](https://github.com/mschirl) contains all exercises for the lecture on Machine Learning held by the ITS master's degree program of Salzburg University of Applied Sciences.


## Usage
If you don't know how to fork a repository properly and just want to work with the files provided in this repo, we suggest you follow these steps in order to avoid possible data loss and merge conflicts when new exercises are uploaded at a later date:

Within your docker container's `notebooks/` directory, call

```
$ git clone https://github.com/mschirl/machine-learning.git
$ cd machine-learning
```

After the repo was successfully cloned and you have thus loaded the templates and example files into your local docker container, copy the file you are about to work on into another directory.
A simple example would be to call

```
$ cp file_to_move.ipynb ..
$ cd ..
```

in the `machine-learning` directory. You can then adapt the path to your dataset within the jupyter notebook and start with your exercises. This also ensures that you won't have to handle merge conflicts later on because you do not change the contents of the original repository folder structure on your machine.

When this is done correctly, calling

```
$ git pull
```

in your `machine-learning` directory should update the local copy of your exercises to the newest version that is currently uploaded to GitHub.

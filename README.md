# FilmspottingMadness
Analytics for [Filmspotting Madness](https://www.filmspotting.net/madness/)

Unlike in a sports tournament, we don't have matches before the tournament to learn from.  
The current approach here is to learn from a subset of the matches of Filmspotting Madness to predict the outcome of other matches, for example the final.
This leaves very few training samples, which is not ideal, so other ideas are welcome!

# To view the current results
To view the current results, simply click on [fs_notebook.ipynb](https://github.com/benjaminkreis/FilmspottingMadness/blob/master/fs_notebook.ipynb).

# To run the code yourself

## Dependencies
The workhorses here are python 3.6, pandas, sci-kit learn, and keras with tensorflow backend.  
If you have conda installed and want to copy my setup exactly (which might be overkill), you can use my conda environment:

```
conda env create -f environment.yml
```

## The data
The data used in training is collected from [The Movie Database (TMDb)](https://www.themoviedb.org/?language=en) 
and [GroupLens](https://grouplens.org/datasets/movielens/latest/).  
I downloaded it from this [Kaggle competition](https://www.kaggle.com/rounakbanik/the-movies-dataset), which is where you can download it too!
It's about 1 GB and should be placed in a directory called `data`.

The results of the [Filmspotting bracket](https://challonge.com/madness2018) are just put in by hand in the notebook itself.


## Run the notebook

The code is in a jupyter notebook, which you can open with:
```
jupyter notebook --ip 127.0.0.1 --port 8899 &
```

# Collaboration welcome!

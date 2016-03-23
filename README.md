![Image of Dato dog logo](https://dato.com/images/dato_logo_124px.png)

# Movie Recommender Sample Project

> This is a Dato sample for recommenders. Explore the [gallery](https://dato.com/learn/gallery/) to see other examples.  

This sample code shows how to build, evaluate, and deploy a
recommender model for movies. You could use this model to power
"Recommended for you" or suggest "Similar Movies" features.

[![Image of explore by item](/assets/explore_items.png)]()


## Get started

1. Before you begin, make sure you have [installed GraphLab Create](https://dato.com/download/),
   a Python package for machine learning.

2. [Download and extract the example code](https://github.com/dato-code/dato-samples/archive/master.zip)
   to a directory on your machine, or clone it with the following command:

   ```bash
   git clone http://github.com/dato-code/sample-movie-recommender
   cd sample-movie-recommender
   ```

3. While in the `sample-movie-recommender` directory, run the following script
   to download the sample project data:

  ```bash
  python download_data.py
  ```

4. Making sure you are working in a Python environment with GraphLab Create installed,
   run the `movie_recommender.py` script to build and explore the recommender model on your machine:

   ```bash
   python -i movie_recommender.py
   ```

   The `-i` flag causes Python to drop into an interactive interpreter
   after the script executes.

   Once the model has been created, a browser window should open
   to let you explore and interact with your recommender model.

   Alternatively, you can also run the provided IPython Notebook:

   ```bash
   ipython notebook movie_recommender.ipynb
   ```

## Learn More and Next Steps

Once you have the sample project running, you can try the following:

  - [Learn more about how the sample works](./LEARN_MORE.md#how-it-works)
  - [Try it on your own data set](./LEARN_MORE.md#use-your-own-data)
  - [Use the model in your app](./LEARN_MORE.md#integrate-with-your-app)


To find out more about building recommender models, check out the
[user guide](https://dato.com/learn/userguide/recommender/introduction.html)
or [API documentation](https://dato.com/products/create/docs/graphlab.toolkits.recommender.html).


## Troubleshooting

If you are having trouble, please [create a Github Issue](https://github.com/dato-code/dato-samples/issues/new)
or start a discussion on the [user forum](http://forum.dato.com/).


## Acknowledgements

The MovieLens dataset was collected by the GroupLens Research Project at the University of Minnesota.

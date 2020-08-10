---
template: overrides/main.html
---

# Machine Learning

## TigerGraph2TensorFlow

=== "Overview"
    This notebook walks through a basic example of using TensorFlow with the output of a graph to run a prediction whether a User will like a movie. The data is collected from a TigerGraph database using a Python package pyTigerGraph. Data collected is via a REST call on a user built query. The output from the call is coming to the notebook in a JSON format. Using Pandas we transform that data into a dataframe. After transforming the data we get the data ready fror consumption for a basic model with 2 layers. The very last step we do a data prediction on some movies the user hasn't rated.

=== "NoteBook"
    <script src="https://gist.github.com/HerkTG/3c9f134487e82b1c9926beb7cff9d7b5.js"></script>
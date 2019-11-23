# Front-End Design
See it here: https://kitrana.github.io/visualdashboard  
  
## About the project  
Data can be visualized without using numbers with a visualization called a word cloud. A word cloud allows you visualize the frequency with which an item appears in a set of data or show the importance of an item in a set of data by using the font size or color of the word to indicate its weight or significance. Word clouds are great tools to use in posters, on a website, or in presentations where the audience you are presenting to does not have a long time to study your visualization.

In this analysis, I used word clouds to show the frequency in which a given category was associated with the movies in the dataset which consisted of movies from the TMDB Top 5000 Movies Dataset as well as elements from the OMDB API.

In order to generate the Wordclouds for this analysis, I used the WordCloud and Pilow libraries in Python. WordCloud allows you to pass a list of strings as they appear in the dataset. WordCloud will then display each string increasing the font size from small to large depending on the frequency. Using Pillow, I was able to import an image and mask the WordCloud over this image.

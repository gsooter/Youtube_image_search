# Video Natural langueage image search algorithm
### Code for Natural language search tool for YouTube videos. 

I worked on this project with MSBA Classmates: Brett Bartol, JT Flume, Jackson Hittner, and Sam LaPlatney.

This project allows you to search a YouTube video for specific frames with natural language search terms. Feel free to use any video and any search term. With a higher "N" the video will run faster, but might skip peices you require. 

Here is a link to a [Medium](https://medium.com/@garrett.sooter/using-natural-language-queries-to-search-videos-and-applications-21f7154303c2) article which will explain this in further detail

In this repo you will find a PPT presentaiton which will give an overview of the project and its application.

This project works with CLIP a pretrained neural network which creates vectors for images which you can match similarity to your desired search term. 

Tere are multiple things you are able to change your self in these programs.

One is N, this is the nunber of frames to skip in the video to reduce the number of total images you are required to parse over. 

Once run you will be able to enter a YouTube link and it should pull up the 3 most likely matches. 

The [notebook](https://colab.research.google.com/drive/1Q9bXlvL84n6c3UzdvIX4L-Cdo4XFgEi4?usp=sharing) will parse the requested video will work nicely and is incredibly fun to play with. 

The [notebook](https://colab.research.google.com/drive/1spu4Z-NPal7LrY9HbmCcA-nSHRHMFP0e?usp=sharing) with the consolidation code only works when you get luck and it finds a cluster that has your search term in it. Please reach out if you find a way to consolidate frames, I am incredibly curious about this and will keep working on it myself as well. 

# Python_Project_for_Scraping_YouTube_Using_the_YouTube_Data_API

In this project, we demonstrate the creation of a Python project focused on scraping YouTube data using the YouTube Data API. We utilize the API to gather data and subsequently load it into a Pandas DataFrame in Python for Analysis. At the end, we use the Seaborn library to create visualizations based on the extracted data.


Step 1

- First, we create a YouTube API Key which will be our credential to access YouTube data.
- Once the API Key is generated, we will see how to use this API key to access different YouTube data.
- We will look at the different sections in the documentation to access different data we need to build this project.
- We will also look at the sample Python code given by Google to call different resources and methods to fetch YouTube data.

Step 2

- Then, we will get into writing the Python code to build this project. 
- Here I have used Jupyter Notebook to write my Python code. 1st we will install all the required Python packages.
- To access YouTube API data in Python, we'll need to install the "google-api-python-client" package. You can do this by running the command: 'pip install google-api-python-client'.

  
Step 3

- 1st we extract channel details from YouTube. I.e. we extract details such as YouTube channel name, total no of subscribers, total views, and total number of videos posted by each channel.
- We gather these details for a few Data Analyst/Data Scientist kind of channels and then compare these channel data with each other.
- We shall see who has the highest number of subscribers and who gets the most views and the amount of videos posted by these channels.
- We will be loading all of this data into a Pandas data frame and then analyzing it. We will also generate some basic visualization using this data so we can easily compare these multiple channels.


Step 4

In the second part of the video, we shall build a logic to extract video details from a particular channel. We shall extract details such as video title, total views each video has got, total number of likes, dislikes and comments each video has got. We shall extract these details for all of the videos posted by a particular channel. We will then analyze this data by loading it into a pandas dataframe. At the end we will create some simple visualization using Seaborn python library.





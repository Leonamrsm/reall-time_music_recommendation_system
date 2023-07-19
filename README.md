# Reall-time Music Recommendation System

In this project, a Real Time Recommendation System was built using PySpark, Spark Streaming and Kafka. The objective is to recommend music according to the preferences of users on Spotfy, but the project can be modified to recommend other products or services.

For this, 2 data streams were used:
* Stream 1 – dataset with thousands of songs. From this dataset, songs will be recommended for the user. The data is taken from the link below:

https://research.atspotify.com/datasets

* Stream 2 – The user's music preferences will be extracted directly from Spotify with the free API provided by the company.

## Tools and APIs used in this project

* Python with jupyter notebook using Anaconda which simplifies package management.

* Apache Streaming for real-time data processing.

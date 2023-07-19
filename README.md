# Reall-time Music Recommendation System

In this project, a Real Time Recommendation System was built using PySpark, Spark Streaming and Kafka. The objective is to recommend music according to the preferences of users on Spotfy, but the project can be modified to recommend other products or services.

For this, 2 data streams were used:
* Stream 1 – dataset with thousands of songs. From this dataset, songs will be recommended for the user. The data is taken from the link below:

https://research.atspotify.com/datasets

* Stream 2 – The user's music preferences will be extracted directly from Spotify with the free API provided by the company.

## Tools and APIs used in this project

* Python with jupyter notebook using Anaconda which simplifies package management.

* Apache Kafka for data streaming management, being an abstraction and management layer that facilitates scalability, fault tolerance and efficient processing of large volumes of data in real time.

* Docker being a lighter and more efficient alternative to traditional virtual machines, allowing applications to run in independent containers, sharing the same kernel as the host operating system. This results in less resource overhead and faster application deployment.

* Spotfy web API to extract user music preferences.


<img src="imges/solution_architecture.png" alt="Descrição da imagem" width="1000" height="450">

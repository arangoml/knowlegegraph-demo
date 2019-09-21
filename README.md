### Building Adaptive Knowledge Graphs

Information within organizations cover various topical domains and knowledge graph projects seek to make all this knowledge accessible. Modern knowledge graphs have to be adaptive and allow for an easy combination of various aspects of information an organization produces – best case, in an ad-hoc fashion.

A combination of JSON stores, semantic search and graph technology is often used to provide native storage and access to data. But these setups tend to be challenging in terms of data consistency and development complexity – therefore hindering the adaptiveness of knowledge graph projects.

Here, you'll get to know how to use a native multi-model database to create a knowledge graph over movie data scraped from Wikipedia by using the graph and semantic search capabilities within ArangoDB. Different aspects of movie metadata can be represented as a graph to essentially process textual information into main components and their relationships. We introduce the new features in ArangoDB, that can play a crucial role in helping users to access the substantial and valuable knowledge from this knowledge graph. We also show the possibilities to enrich this knowledge further with e.g. plot summaries for building ML engines like Recommendation system, Text Classification etc.



The Jupyter Notebook contains the following:

* Setting up Python environment - importing libraries and first look at the raw dataset 

* Import dataset to ArangoDB

* Preprocessing raw data

    * Using ArangoQL
    
    * Connecting with Python using PyArango

* Data exploration with the features of ArangoDB.
    
    * Graph visualization
    
    * ArangoSearch example
    
    * K-shortest path example
    
    * Pruned search

* Machine Learning tasks
    
    * Movie similarity based on plots using Tensorflow. 
    
    * Genre classification based on plots using -
    
        * scikit-learn
        
        * Tensorflow


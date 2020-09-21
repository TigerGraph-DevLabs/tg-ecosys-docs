---
template: overrides/main.html
---
<!-- As a Community Member Feel free to add anything that you think would help others in the community -->
# Awesome TigerGraph
[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of AWESOME TigerGraph community resources. 

## Table of Contents
* [**Communties**](#communities)
* [**TigerGraph Resources**](#tigergraph-resources)
* [**Developer Tools**](#developer-tools)
* [**Connectors**](#connectors)
* [**Visualizations**](#visualization)
* [**Enviornments**](#enviornments)
* [**Certifications**](#certifications)
* [**Pre-Built Demos**](#demos)
* [**Benchmarking**](#benchmarking)
* [**Blogs**](#blogs)
* [**Videos**](#videos)


## Communities
* [**TigerGraph Community Site**](https://community.tigergraph.com/) a Forum allowing for Q&A, deep discussion about GSQL and TigerGraph's platform components
* [**YouTube**](https://www.youtube.com/tigergraph)
* [**LinkedIn**](https://www.linkedin.com/company/tigergraph/)
* [**Twitter**](https://twitter.com/TigerGraphDB)
* [**Facebook**](https://www.facebook.com/TigerGraphDB/)
* [**Discord**](https://discord.gg/F2c9b9v)
* [**Reddit**](https://www.reddit.com/r/tigergraph/)

## TigerGraph Resources
* [**Getting Started Guide**](https://community.tigergraph.com/t/tigergraph-getting-started-guide/11) a helpful guide walking you through getting started with TigerGraph
* [**TigerGraph Documentation**](https://docs.tigergraph.com/) - TigerGraph's main documentation
* [**Graph Algorithms**](https://github.com/tigergraph/gsql-graph-algorithms) TigerGraph's Open Source Algorithiums
* [**Starter Kits**](https://www.youtube.com/playlist?list=PLq4l3NnrSRp5SMFUp3YLQRj5SBYbnB7fU) Starter Kit Overview
* [**User Defined Function Library**](https://github.com/tigergraph/ecosys/tree/master/UDF) UDF's you can use in your TigerGraph instance
* [**GSQL Videos**](https://www.youtube.com/playlist?list=PLq4l3NnrSRp6vaCWmookIZJefDkAPvaxS) learn GSQL
* [**GSQL Webinars**](https://www.youtube.com/playlist?list=PLq4l3NnrSRp4IGO-CgwjRa1JqxN-vWATx) 
* [**Blog**](https://www.tigergraph.com/blog/) TigerGraph's Blog

## Developer Tools
### Build
* [**Giraffle**](https://github.com/Optum/giraffle) a dsl build tool that allows you to develop in multi-graph and multi-instances of Tigergraph
* [**Automatic Demo Loader**](https://devpost.com/software/automatic-demo-loader) a Google Colab notebook that can automatically upload a demo(from the TG demos folder in ecosys on Github). The notebook comes with widgets so no coding is required(just click buttons)

### CLI
* [**TigerGraphCLI**](https://github.com/frankfka/TigerGraphCLI) an easy-to-use CLI for interacting with TigerGraph databases

### IDE
* [**vsc-gsql-extension**](https://github.com/DavidBakerEffendi/vsc-gsql-extension) an extension that provides syntax highlighting capabilities for TigerGraph's GSQL
* [**gsql-vim**](https://github.com/jmeekhof/gsql-vim) a vim GSQL syntax highlighting tool
* [**atom-language-gsql**](https://github.com/alejandropoveda/atom-language-gsql) adds syntax highlighting and snippets to GSQL® files in Atom
* [**gsql-sublime**](https://github.com/fjblau/gsql-sublime) - syntax formatter for GSQL in Sublime v3

### Python
* [**GSQL Schema Extractor**](https://colab.research.google.com/drive/1Cm-rFTSUJPFFtPx0R_Wqj9MilTCLFE3_?usp=sharing) a python script to extract graph schema and modify extraction into a GSQL schema

## Connectors
### Kafka
* [**tg-kafka-connect**](https://github.com/tigergraph/ecosys/tree/master/tools/etl/tg-kafka-connect/com/tigergraph/connector) a Kafka connector

### s3
* [**tg-s3-parquet-load**](https://github.com/tigergraph/ecosys/tree/master/tools/etl/tg-s3-parquet-load) a program that uses Spark SQL to load parquet from Amazon S3 and store as CSV locally or in S3

### RDBMS
* [**tg-rdbms-import**](https://github.com/tigergraph/ecosys/tree/master/tools/etl/tg-rdbms-import) a utility to read records from a RDBMS and then POST to TigerGraph

### Hadoop/Spark
* [**tg-hadoop-connect**](https://github.com/tigergraph/ecosys/tree/master/tools/etl/tg-hadoop-connect) a utility to read csv files from Hadoop and then POST to TigerGraph
* [**tg-jdbc-driver**](https://github.com/tigergraph/ecosys/tree/master/tools/etl/tg-jdbc-driver) a JDBC Type 4 Driver for Spark, Python and Java

### Python
* [**pyTigerGraph**](https://pypi.org/project/pyTigerGraph/) Recommended
* [**tg-python-wrapper**](https://github.com/tigergraph/ecosys/tree/master/tools/etl/tg-python-wrapper) simple python wrapper
* [**gsql_client**](https://github.com/dingmaotu/gsql_client) simple python gsql client
* [**pyGraphistry**](https://github.com/graphistry/pygraphistry/tree/master/demos/demos_databases_apis/tigergraph)

### .NET
* [**TigerGraph.NET:**](https://github.com/allisterb/TigerGraph.NET) Cross-platform libraries and tools for building graph-powered browser, server, desktop, and notebook apps in C# and F# with TigerGraph.

### C#
* [**TigerGraphConnector_CSharp**](https://github.com/gpadvorac/TigerGraphConnector_CSharp) - C# Wrapper for the TigerGraph REST++ API

### Javacript
* [**tigroid**](https://github.com/szb-tg/Tigroid.js) a connector is intended to work both in browsers and on server side, to be Node.JS friendly (in the long term).
* [**TigerGraph.js**](https://genericp3rson.github.io/Tigergraph.js/) a Javascript wrapper for TigerGraph aimed to simplify the TigerGraph-JavaScript development process

### Flutter
* [**tiger_graph**](https://pub.dev/packages/tiger_graph) a Dart wrapper that streamlines connection between a TigerGraph cloud instance and Flutter.

### Other
* [**dist_split**](https://github.com/tigergraph/ecosys/tree/master/etl/dist_split) a utility to split large data files for loading onto a distributed system

## Visualization
* [**Davraz**](https://github.com/canbax/davraz) a graph visualization and exploration tool
* [**D3**](https://github.com/d3/d3/wiki/Gallery) a community open source visualization library
* [**ant_design_g6**](https://g6.antv.vision/en/docs/manual/introduction) graph visualization engine, which provides a set of basic mechanisms, including rendering, layout, analysis, interaction, animation, and other auxiliary tools
* [**KeyLines**](https://cambridge-intelligence.com/keylines/)
* [**Gephi**](https://gephi.org/) a visualization and exploration software for all kinds of graphs and networks. Gephi is open-source and free
* [**vis.js**](https://visjs.org/) a dynamic, browser based visualization library
* [**py3plex**](https://github.com/SkBlaz/Py3plex) a library for analysis and visualization of heterogeneous networks
* [**pyGraphistry**](https://github.com/graphistry/pygraphistry/tree/master/demos/demos_databases_apis/tigergraph) a python based GPU powered graph visualization packackage for large graph rendering

## TigerGraph Enviornment
### Docker
* [**Docker Demo**](https://github.com/tigergraph/ecosys/tree/master/demos/guru_scripts/docker) step-by-step instructions on how to pull the latest TigerGraph Developer Edition docker image to your host machine
* [**TG Docker Lite**](https://github.com/DavidBakerEffendi/tigergraph) the purpose of this repository is to remove un-needed demo files from TigerGraph containers for resource sensitive environments e.g. CI/CD. The Docker image starts gadmin when the container spins up
* [**Full Enviorment Workshop**](https://github.com/xpertmind/TigerGraph) TigerGraph workshop with TG-Developer latest version (3.0) and the ecosystem around it: MariaDB, Kafka, Zookeeper, Kafka Connect and Conda

### Cloud
* [**Deploy TigerGraph Cloud**](https://community.tigergraph.com/t/howto-deploy-a-cloud-instance/363) a walkthrough guide on navigating tigergraph cloud

## Certifications
* [**Graph Fundementals**](https://www.tigergraph.com/certification-graph-fundamentals/) a course designed for people who are new to graph database and graph-based analytics
* [**GSQL 101**](https://www.tigergraph.com/certification-gsql-101/) provides the basics of programming in GSQL, and enables you to create and use TigerGraph’s graph database and analytics solution

## Demos
* [**TigerGraph Yelp Dataset Solution**](https://github.com/DavidBakerEffendi/tigergraph-yelp) contains the GSQL scripts and TigerGraph solution tarball to import and model the Yelp challenge dataset using TigerGraph
* [**GSQL 101 Python Google Colab**](https://colab.research.google.com/drive/1E8tTIvg-DI8zpmyQjtxVXpP8KqtjXxY8?usp=sharing) a getting started guide for interacting with TigerGraph from python environment
* [**pyGraphistry Vis Demo Notebook**](https://github.com/graphistry/pygraphistry/blob/master/demos/demos_databases_apis/tigergraph/tigergraph_pygraphistry_bindings.ipynb) a sample of how to add graph based visualizations in your notebook
* [**pattern_match**](https://github.com/tigergraph/ecosys/tree/master/demos/guru_scripts/pattern_match) a bunch of sample GSQL hops
* [**temporal_data**](https://github.com/tigergraph/ecosys/tree/master/demos/guru_scripts/temporal_data) a temporal data demo used in Graph Guru 10
* [**pagerank**](https://github.com/tigergraph/ecosys/tree/master/demos/guru_scripts/pagerank_demo) a healthcare demo demonstrating 
* [**label_propagation**](https://github.com/tigergraph/ecosys/tree/master/demos/guru_scripts/comm_dect_demo) a healthcare demo that illustrates how to find communities
* [**loop_detection**](https://github.com/tigergraph/ecosys/tree/master/demos/guru_scripts/loop_detection_demo) a demo focused on loop detection using GSQL queries
* [**movie_reccomendation**](https://github.com/tigergraph/ecosys/tree/master/demos/guru_scripts/movie_recommendation) a classic graph based movie recommendation engine
* [**network_IT**](https://github.com/tigergraph/ecosys/tree/master/demos/guru_scripts/network_IT_resource) a demo outlining how you can use graph to manage IT networks
* [**deep_learning**](https://github.com/tigergraph/ecosys/tree/master/demos/guru_scripts/guru19_deep_learning) a demo that walks you through building a neural network to recognize handwritten digits
* [**RDF**](https://github.com/tigergraph/ecosys/tree/master/demos/guru_scripts/RDF) a peek into doing RDF representation in TigerGraph
* [**pattern_interpret**](https://github.com/tigergraph/ecosys/tree/master/demos/guru_scripts/guru15_pattern_interpret) a few examples of Pattern Matching and Interpreted Mode GSQL
* [**fraud_detection**](https://github.com/tigergraph/ecosys/tree/master/demos/guru_scripts/fraud_detection_demo) a look at how you can use graphs for fraud detection
 [**TG-bot**](https://devpost.com/software/tg-bot) a TigerGraph-chat bot model

## How To
* [**Python Schema & Load**](https://github.com/parkererickson/yelpGraph/blob/master/schemaAndLoad.ipynb) a simple walkthrough of creating a schmea and upserting data
* [**GSQL101 - on a Jupyter Notebook**](https://github.com/yaniv256/ecosys/blob/master/demos/guru_scripts/docker_notebook/gsql101.ipynb) a guide to using GSQL with a Jupyter Notebook

## Benchmarking
* [**Suitability of Graph Database Technology for the Analysis of Spatio-Temporal Data**](https://www.mdpi.com/1999-5903/12/5/78) this paper investigates whether or not graph database technology is better suited when compared to the extended relational approach

## Blogs
* [**Modeling Healthcare Data with Graph Databases**](https://towardsdatascience.com/modeling-healthcare-data-with-graph-databases-3e3695bcae3c)
* [**Create a Graph Data Pipeline Using Python, Kafka and TigerGraph Kafka Loader**](https://medium.com/@kel_70824/create-a-graph-data-pipeline-using-python-kafka-and-tigergraph-kafka-loader-bf9e031d16fd)
* [**Graph Technologies are Helping Sunset CISC**](https://medium.com/@dmccreary/graph-technologies-are-helping-sunset-csic-cc128ce25cfc)
* [**Calling TigerGraph through REST Endpoints using POSTMAN**](https://docs.google.com/document/d/1aFG1FBdQ5aO4dwlWdtpcxX6BlF7piFkM8Q5SODhfnS0/edit?usp=sharing)
* [**Update TigerGraph Vertex Data Via REST API Using AWS Alexa**](https://link.medium.com/hlZ62ITMA7)
* [**Migrating to Giraffle for TigerGraph (Remote TigerGraph Part 1)**](https://medium.com/@ramapitchala/migrating-to-giraffle-for-tigergraph-remote-tigergraph-part-1-82b55a5bc219)
* [**How to Import a Graph Solution into TigerGraph Cloud**](https://medium.com/@akash_kaul/how-to-import-a-graph-solution-into-tigergraph-cloud-33108bb8a208)
* [**Designing Feed Relationships with Graph Databases (Full Stack TigerGraph Part 2)**](https://medium.com/@ramapitchala/designing-feed-relationships-with-graph-databases-full-stack-tigergraph-part-2-d8ebeacd2cdf)
* [**Developing a Dynamic Author Search of Covid-19 Articles using Plotly Dash & TigerGraph (Part 4)**](https://towardsdatascience.com/developing-a-dynamic-author-search-of-covid-19-articles-using-plotly-dash-tigergraph-part-4-34e240882a06)
* [**Tiger Graph + Streamlit → Dynamically Visualize South Korea COVID-19 Data**](https://medium.com/@rhnshiva/tiger-graph-streamlit-dynamically-visualize-south-korea-covid-19-data-c197f1200e27)
* [**Generating Synthetic Patient Data**](https://towardsdatascience.com/generating-synthetic-patient-data-b7901c3bd397)
* [**Full Stack TigerGraph Part 1**](https://medium.com/@ramapitchala/full-stack-tigergraph-part-1-d70718111051)
* [**Using scispaCy for Named-Entity Recognition (Part 1)**](https://towardsdatascience.com/using-scispacy-for-named-entity-recognition-785389e7918d)
* [**Linking Documents in a Semantic Graph (Part 2)**](https://towardsdatascience.com/linking-documents-in-a-semantic-graph-732ab511a01e)
* [**Graph Query Searches (Part 3)**](https://towardsdatascience.com/graph-query-searches-part-3-a8bff845c3f1)
* [**Predicting Initial Public Offerings Using Graph Convolutional Neural Networks**](https://towardsdatascience.com/predicting-initial-public-offerings-using-graph-convolutional-neural-networks-42df5ce16006)
* [**Infection Chains: Discovering the Unknown using Graph Analytics**](https://www.linkedin.com/pulse/infection-chains-discovering-unknown-using-graph-analytics-herke/)
* [**Build your First Cloud-Native Graph Database**](https://www.linkedin.com/pulse/build-your-first-cloud-native-graph-database-jonathan-herke/)
* [**Deploy a Graph Database in 3 Steps [No Code Needed]!**](https://www.linkedin.com/pulse/deploy-graph-database-3-steps-code-needed-jonathan-herke/)
* [**Power BI App**](https://devpost.com/software/power-bi-app-over-tigergraph-database) an app enabling data analyst to analyse Graph Database based on query ands populate it in PowerBI

## Videos
* [**TigerGraph YouTube Channel**](https://www.youtube.com/tigergraph)

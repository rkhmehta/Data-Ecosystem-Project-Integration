# Data-Ecosystem-Project-Integration

This repository encompasses Knime workflows for extracting data from Yelp and NFT Sales, establishing a data table on a MongoDB Cloud Cluster, and generating insights through Knime. The project involves the integration of Yelp data and sales data of a specific NFT.

### Features:

MongoDB Cluster Setup:
Establishment of MongoDB clusters for both Yelp and NFT Sales data.
Extraction of Yelp data using Knime and loading it into a personal MongoDB cluster.
API link setup between Python instance and Flipside data access endpoint for NFT Sales data extraction.
Conversion of extracted NFT Sales data from JSON to a DataFrame and loading it into the MongoDB cluster.

Knime Workflow Setup:
Creation of two Knime workflows—one for Yelp DataBase and another for NFT Sales Insights.
Workflow files available in the repository for easy understanding and replication.

### Approach:

Step 1: Setup MongoDB Clusters

Yelp Data Loading:
Extraction of Yelp data using Knime.
Loading Yelp data into a personal MongoDB cluster.

NFT Sales Data Loading:
API link setup between Python instance and Flipside data access endpoint for NFT Sales data.
Extraction of NFT Sales data based on the project name ("Pudgy Penguins").
Conversion of extracted data to a DataFrame and loading it into the MongoDB cluster.

Step 2: Knime Workflow Setup

Yelp DataBase Workflow:
Knime workflow dedicated to handling Yelp data.
Extracting, transforming, and loading Yelp data for further analysis.

NFT Sales Insights Workflow:
Knime workflow focused on generating insights from NFT Sales data.
Analyzing and visualizing sales data to derive meaningful insights.

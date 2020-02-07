# Raghava Documentation
:octocat: Documentation by Raghava


### Week 1 - Tutorials/Introduction
- Learnt and went through intro tutorials for NetworkX, Neo4j and what ICD 11 API - for foundation data and MMS data
- Introduced to MongoDB and Elasticsearch.

### Week 2 - Data Management
- Ran Python scripts to download data from the ICD 11 API 
- Parsed raw json files to readable format
- Pushed local data to MongoDB

### Week 3 - Tree Development and Search Algorithm
- Imported the json file into a NetworkX graph and made each disease into a single node with childs as edges
-  Created a list of dictionaries corresponding to the diseases in ICD11
- Wrote a recursive function to extract all cardiovascular diseases from the nodes and stored the IDs in a separate list

### Week 4 - Tree Parsing and Advanced AI Search Algorithms
- Used the list of cardiovascular diseases created last week to create a hierarchical tree in NetworkX starting from the Root Cardiovascular code as taken from the ICD 11 Browser
- Plotted the tree to visualize the hierarchy and the spread of diseases
- Created a list of all paths (shortest) from the root node to different leaf nodes to gauge number of children per root
- Conducted some EDA to map codes to their titles and get a count of first degree children per root disease 
- Plotted simple bar and bubble plots to visualize the diseases with the maximum number of childs. 
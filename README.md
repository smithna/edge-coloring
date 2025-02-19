# edge-coloring

This repository accompanies the blog post "Solve scheduling problems with relationship coloring and Neo4j."

To execute the code, clone the repository and set environment variables NEO4J_URI, NEO4J_USER, NEO4J_PASSWORD, NEO4J_DATABASE pointing to a Neo4j environment. 
The environment could be a [Neo4j Aura free tier instance](https://neo4j.com/product/auradb/) a local [Neo4j Desktop instance](https://neo4j.com/download/), or another Neo4j instance of your choosing.

Run the load_B1G_games.ipynb notebook to download data about the 2024 Big 10 football schedule to Neo4j.

Next, run the misra_gries.ipynb notebook to color the relationships.

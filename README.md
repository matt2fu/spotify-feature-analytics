# spotify-feature-analytics

This project focuses on Spotify artists. We wanted to find the "Kevin Bacon number" equivalent for Spotify artists that worked together i.e. were featured on the same song.

For this project, we used two datasets: edges.csv and nodes.csv. Edges.csv contains data on artists that are featured on the same song, it is in the form of an edge list of artist ids. Nodes.csv contains data on the Spotify artists, their id, name, etc.

We then used BFS to analyze the shortest path i.e. the number of connections between different artists.

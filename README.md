# Embedding Visualizations for Steam Games
The game descriptions are embedded using a Sentence Transformer. Then they are visualized using multiple dimension reduction techniques such as PCA, t-SNE and PaCMAP. 

The model is also fine tuned on a variety of generated queries to be able to search for games based on their genre as well. Last, LIME is used to explain the parts of the query and description that lead to the game being searched.

The dataset is taken from: https://www.kaggle.com/datasets/nikatomashvili/steam-games-dataset
Put the data into a `data/steam_games.csv` folder.
# The_Witcher
Community Mapping of the characters in the eight books

Create a web-driver driect it to fan page of witcher at 
https://witcher.fandom.com/wiki/Category:Characters_in_the_stories

Create a list of books with book name and book-link
Create a character list 
Pass book name and charachter name to dataframe

Iterate through sentences of book(s) and create DataFrame of entities
Filter entities passed from entities in book to match names from character dataframe
Create dataframe of Relationships over a window of 5 sentences
Group relationships and assign a count by occurances (to pass as node size)

Using pyvis for interactive network graph
https://pyvis.readthedocs.io/en/latest/tutorial.html#getting-started

Graph characters as nodes and visualise using kamada_kawai_layout
https://networkx.org/documentation/stable/reference/drawing.html

Set node attributes: size and communities - using community_louvain.best_partition()
https://networkx.org/documentation/stable/reference/algorithms/generated/networkx.algorithms.community.louvain.louvain_communities.html#networkx.algorithms.community.louvain.louvain_communities
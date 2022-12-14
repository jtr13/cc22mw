# Visualizing graphs and networks

Vritansh Kamal

Link to presentation and resources :- <https://docs.google.com/presentation/d/1LOT2tx0TrxtLs3Dks0rEN04_WKYvzp9wCJ0amissUo0/edit#slide=id.p>

## Motivations

For the community contribution, I have decided to give a presentation on visualizing networks for EDAV. I've explored some of these open-source tools, as a part of my research in industry.

Graphs can reveal highly complex relationships when explored using the right kind of tools. This involves visualizing the graphs(networks) which are different than our traditional visualization methods. From visualizations, we should be able to understand the clusters that these graphs form, and the shortest path, and extract relevant information about how our data is structured. I discovered it has many more use cases in the evergrowing industry of Industrial IoT, bank transactions, and blockchain. There are server-side tools that can perform really well. But the challenge is to create visualizations on the browsers using javascript to create scalable and tangible products in a saas environment.

These visualizations make use of the user's CPU/ GPU to perform the computation for visualizing data. There are libraries like CytoscapeJS, D3Js-force graph, etc. but these don't scale very well when the size of nodes and edges in a graph increases. These tools perform slowly on browsers or crash frequently when the size of graphs increases.

I found this library from Vasco Asturiano which is open-source with MIT License and has support for rendering webGL-based graphs. This helps to solve most of the problems with its ability to interact with GPU. It can help visualize graphs with ease in the order of tens of thousands of nodes and edges. It also includes the customizations such as adding images on the links and nodes, adding particles emission, etc. This helps to bring virtual graphs as much as possible close to the real world.

#Learning
This is an efficient library, Which forms abstraction on top of d3js components and provides scalability. If I had more time I would have explored on it and built a prototype using any network dataset. The key to analyze networks is to identify relationships and display them accordingly. 


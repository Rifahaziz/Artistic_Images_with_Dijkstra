# Artistic_Images_with_Dijkstra
Creating artistic images with Dijkstra's algorithm, with nodes dispersing simultaneously to create regions (often like Voronoi Diagrams). 
The edges with Voronoi diagrams are straight-edged, but with Dijkstra's algorithm the region borders are more random. 

A method for creating artistic and abstract texture images from scratch is proposed with the motivation from naturally occuring microscopic texture images.
Thin sections of rocks portray an abstract art with significant amount of randomness and irregularity, which is re-created through the use of a shortest 
path algorithm with various cost functions. Experiments are carried out to produce grayscale images by changing the cost functions of the algorithm and 
using different distribution of the edge weights to favour different variants of the segments. Six different cost metric changes are applied to modify 
the existing Dijkstra’s algorithm for the formation of different site regions. The goal is to create abstract and artistic images similar to the texture 
images collected from Carleton University. The method is inexpensive and faster compared to recreating images with neural network models, such as 
Generative Adversarial Networks (GANs).



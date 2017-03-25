# Plexus #

## Project Description ##
Project mainly results in finding indirect composite relations for a particular node in an ego network.
This particular project mainly focuses on **Friend** relation and finds and indirect friendship relation between several egos in an ego network.

## Result ##
Upon the action of the algorithm on the dataset the user will be able to find friend connections up-to a limit (l)

For instance,

** if l = 1 **
  **Result** => Direct Friends (1st Connection)

**if l = 2**
  **Result** => Friends of Friends (2nd Connections
  
**if l = 3**
  **Result** => Friends of Friends of Friends

and so on....

## TODOs ##

- [x] Understand the basic framework of the dataset
- [x] Implement Algorithm on the dataset
- [x] Publish applicable results in the form of graphs with appropriate parameters
- [x] Development of a proper UI showing traversal of each node with the progress of the algorithm 

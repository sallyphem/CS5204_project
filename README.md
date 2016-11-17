# CS5204_project

optimize ART operation search_by_value with BFS, example is changed to fit ART, specifically, finish the queue after finding the element;
bfs_sample works for ordinary binary tree separately;
added main function to art.c for a simple test

update: cannot solve "lazy expansion", i.e. a single long path is combined to a single leaf, use DFS instead;
DFS is given at the end of art.c

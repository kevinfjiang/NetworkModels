# Income Inequality Project
Hi everybody, here's the 3rd update, I'll explain all the files
Note, i'm still kinda new to github so i'm not sure if this works because I have the packages installed

To Run: 
    
    python get_graph.py <command line argument>
Note Please do not exceed 60 or so nodes, as it starts taking a really long time

Command line arguments(Capitalization Matters):
    
    'R' for Robustness, no quotes
    'N' for Network Connectivity
    'E' for Efficiency
    Nothing to just get data in a file on your desktop called 'dataframe'

## How it works:          
Basically gets inputs from user, on the starting number nodes and
increments up by the input increment until the total number of nodes        
It creates an Min spanning tree on of the nodes at random and randomly adds edges 
with makeRandomEdge     
Then it collects all the data and graphs 1 of the 3 measures above. I'll try to add the
capability to mix and match and graph multiple later


**Robustness:**
The current measures of robustness is the critical fractiton of nodes removed and 
netwwork connectivity from this paper: https://arxiv.org/abs/0802.2564


**Efficiency:**
The efficiency SPECON paper from 2004 that Prof gave us.
Dylan, I'll try to add your latest paper and a few measures

Feel free to modify the code. You can access the matrix in efficiency or robustness 
and create your own functions with Graph.graph[i][j] to access specific coords. If 
you need to set a specific part of the matrix to something use Graph.addEdge([i,j], length)
If you need to create a parallel graph just create a new graph with new = Graph(n) and set
new.graph = Graph.graph to create a copy. Also feel free to add to anything else. Sorry if it's messy!


# Network Moodel
Hi everybody, here's the 3rd update, I'll explain all the files

To Run: 
    
    python get_graph.py <command line argument>

Command line arguments:
    
    'R' for Robustness, no quotes
    'N' for Network Connectivity
    'E' for Efficiency
    Nothing to just get data in a file on your desktop called 'dataframe'

## How it works:          
Basically gets inputs from user, on the starting number nodes and
increments up by the input increment until the total number of nodes        
It creates an Min spanning tree on of the nodes at random and randomly adds edges 
with makeRandomEdge     
Then it collects all the data and graphs 1 of the 3 measures above.


**Robustness:**
The current measures of robustness is the critical fractiton of nodes removed and 
netwwork connectivity from this paper: https://arxiv.org/abs/0802.2564


**Efficiency:**
The efficiency SPECON paper from 2004 that Prof gave us.
and newly introoduced efficiency papers found by Dylan

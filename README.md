# Complex Networks final project

Project realized for the course *Complex Networks* at *Universitat Politècnica de Catalunya*. 
 
The project is about a Susceptible-Infected (SI) simulation on top of a temporal mail exchange network, containing mail messages exchanged  
between users at specific Unix timestamps.
 The goal of the project is to explore the dynamics and properties of the SI  
simulation by using a real temporal data (taken from [networkrepository](https://networkrepository.com/%20comm-linux-kernel-reply.php)) by:  

 - analyzing the characteristics of the infection prevalence curves  
 - analyzing the role of the network nodes in the virus spreading  
 - analyzing the possibility and the importance of immunizing specific nodes  
 - analyzing nodes infection times in relation to several parameters  
 - analyzing roles of the infection probability on the SI simulation 
 

The implementation is performed in the following order:  
 - at first, we perform a detailed exploratory analysis of the considered network, in order to fully understand its characteristics and main properties.  We  visualize plots of the networks and of its distribution, and also of the main networks centrality measures.  
 - then, we implement the SI simulation process and we run our experiments  
one by one.  

All the functions are implemented in Python,  by building a notebook (`notebook.ipynb`) and by using two auxiliary Python files (`simulation_utils.py` and `network_utils.py`, containing definitions of  helper functions for performing plots and some simulations).

 
For in-depth explanation of the work performed, please refer to the provided [`report.pdf`](https://github.com/denaldo98/cn-project/blob/main/report.pdf) file.


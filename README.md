# congressional_network_analysis
This is the repository for my final project for Social Network Analysis (PPOL 602) at Georgetown University, Spring Session 2023. The goal of the project is to create a dynamic network model for congress in the 21st century. 

## Step 1
First we will use the congress api to generate an edgelist. Specifically, we will first gather all members of the congress available on the api. Next, we will remove congresspeople who did not serve after 2013. Then we will collect all legislation that each member sponsored (again removing all legislation from before 2013). After this we will search for cosponsors for each bill. 

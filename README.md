# congressional_network_analysis
This is the repository for my final project for Social Network Analysis (PPOL 602) at Georgetown University, Spring Session 2023. The goal of the project is to create a dynamic network model for congress in the 21st century. 

## Step 1
First we will use the congress api to generate an edgelist. Specifically, we will first gather all members of the congress available on the api. Next, we will remove congresspeople who did not serve after 2013. Then we will collect all legislation that each member sponsored (again removing all legislation from before 2013). After this we will search for cosponsors for each bill. 


Current To-do List (deadline is Tuesday at 6pm):
1. Iterate through any missing members in the sponsors list.
2. Iterate through any missing bills in the cosponsors list (perhaps also collecting bill type).
3. Iterate through all the bills and collect the legislation's outcome.
4. Create the final dataframe (and create subsets by session of congress). Include the names for each bioguide_id and their party.
5. Create a dictionary of congress number with start and end years.
6. Create a node list of each congress with bio id.

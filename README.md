# congressional_network_analysis
This is the repository for my final project for Social Network Analysis (PPOL 602) at Georgetown University, Spring Session 2023. The goal of the project is to create a dynamic network model for congress in the 21st century. 

## Step 1
First, we will scrape the congressional website using selenium. While there is a congressional api, it does not provide the sufficient level of detail for bill sponsorship and cosponsorhip (specifically the dates associated with these actions). While BeautifulSoup was considered as an alternative, it appears that the website has put restrictions in place to prevent scraping. If the selenium scraping doesn't work, the API will be reconsidered and BeatifulSoup workarounds will be reconsidered. 

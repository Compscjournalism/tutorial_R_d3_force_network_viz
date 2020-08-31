# tutorial: From R to a d3-based force-network visualization
We provide a tutorial on our workflow to generate force-networks in D3,  starting with data in R data


### What this tutorial shows

Working on different stories and visualizations at compscjournalism.org, (social) networks are one of our highly favored types of visualizations. With a stronger background in R-programming and a desire to tell stories on digital platforms in an intuitive, interactive fashion, we developed a workflow combining data preparation and analysis in R and visualization of networks using Javascript, in particular D3.  Here, we present this workflow starting from sample data of a social network in R, right until the visualized SVG (based on JS and D3) in an.html document. The resulting visualization can be found here


### Tutorial/workflow structure

* Data preparation in R, creating a JSON object

* Creating a social network visualization in D3

Within the following section, I will go through these sections briefly and link you to the more detailed tutorials on R and D3 that cover the workflow in greater detail. 


### Data preparation in R

To illustrate the workflow, we use a sample dataset on basketball players and social relations based on teammembership over the course of the player's careers. Thus, nodes represent single players and ties between them indicate those players to have played together in a team a some point of their career. The sample data is uploaded here as an RData object (sample_data.RData). 
The data preparation and the creation of a JSON object is described in great detail in the tutorial_r_side files (both as compiled .html and raw R-markdown file). Find these attached in the resources folder.


### Creating a social network visualization in D3
Once the .json object (graph_data.json is attached in the resources folded) is created, we can turn to the Javascript/D3/HTML side of the process. See the network_viz.html document in the resources folder that contains the source code for generating the network visualization. Is is important to consider the options given by CSS and D3 itself, to change the visualization in any regards. What we publish here is a rather a template that we adapt then depending on the project context. 









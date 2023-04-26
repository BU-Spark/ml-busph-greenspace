# Using Satellite and Street View Imagery to Estimate Greenspace Ecosystem Services in K-12 Schools Project Outline


## Christina Xu, Chengyu Zhang, Haodong Chen, Kuangfei Long, 2023-02-08 vx.x.x-dev_

## Overview

The goal of this specific machine learning project is to characterize ecosystem services (ES) disparities in K-12 schools in the US using satellite and street view imagery and ML image understanding techniques. 

1. Situation and current issues

Greenspace provides benefits across a range of ecosystem services, but little is known about its impact on student learning in K-12 schools, due in part to the lack of interdisciplinary work necessary to study the full pathway from ecosystem mechanisms to learning outcomes benefits. Additionally, although scientists know there are racial and economic disparities in greenspace in environmental justice and communities impacted by historic racist practices (e.g. redlining), nothing is known about disparities in ES mechanisms. 

2. Key Questions
* What is the distribution of greenspace ES across K-12 schools in Boston? In Chelsea? Is it different by state/climate zone? Does one type of ES dominate?
* Are there schools with low ES located in urban heat island or air pollution hot spots? 
* What is the best and appropriate way to utilize the image analysis to inform civic investment? (derived from this question - how should cities prioritize investing in greenspace around schools based on lack of ES? (Thoughts/how does the data help inform this)

3. Hypothesis: Overview of how it could be done
Create a summary or queryable demonstration of what greenness ES for all K-12 schools in Boston & Chelsea means

4. Impact
* Support the several ongoing environmental health research studies at BUSPH
* Provide a resource for schools and policy makers to make equity based sustainability and climate adaptation decisions related to the type of greenspace surrounding schools
* Support future studies linking learning and health outcomes

### A. Problem Statement: 

Outdoor greenspace has become a focus of attention to improve the kindergarten through grade 12 (K-12) school environment and increase sustainability of school campuses. Greenspace provides benefits across a range of ecosystem services, but little is known about its impact on student learning in K-12 schools, due in part to the lack of interdisciplinary work necessary to study the full pathway from ecosystem mechanisms to learning outcomes benefits. Additionally, although scientists know there are racial and economic disparities in greenspace in environmental justice and communities impacted by historic racist practices (e.g. redlining), nothing is known about disparities in ES mechanisms. This project is part of several ongoing environmental health research studies at BUSPH, to study the impact of built environment and indoor environmental quality in K-12 schools on learning and health, with a sustainability and equity focus. 

### B. Checklist for project completion

- [ ] Develop image understanding techniques to start producing the following information: multiple greenspace ES metrics related to temperature and air pollution (regulatory ES)  as well as physical activity and restorative capacity (cultural ES). 

    - [ ] Prepare datasets to be used in the analyses

    - [ ] Implement, train and evaluate computer vision and image understanding models that can provide insights on the following greenspace ES metrics related to temperature and air pollution (regulatory ES)  as well as physical activity and restorative capacity (cultural ES). 

- [ ] The results should show some kind summary or queryable demonstration of what greenness ES for all K-12 schools in Boston & Chelsea means

1. Deliverable 1
   
   First develop image understanding techniques to start producing the following information: multiple greenspace ES metrics related to temperature and air pollution (regulatory ES)  as well as physical activity and restorative capacity (cultural ES). Specifically creating data layers for general greenness, tree canopy, playgrounds & playing fields, and greenspace “view” from schools.

    Implement, train and evaluate computer vision and image understanding models that can provide insights on the following greenspace ES metrics related to temperature and air pollution (regulatory ES)  as well as physical activity and restorative capacity (cultural ES). 



2. Deliverable 2

    Overall the final deliverable is a dataset about the greenness of those sch

    The results should show some kind summary or queryable demonstration of what greenness ES for all K-12 schools in Boston & Chelsea means. 

    This “database” will be a resource for schools and policy makers to make equity based sustainability and climate adaptation decisions related to the type of greenspace surrounding schools. 


### C. Provide a solution in terms of human actions to confirm if the task is within the scope of automation through AI. 

If the project was done by humans instead of AI, it would require certain actions to accomplish the goal.

1. Identifying Ecosystem Services: We would first need to identify the ecosystem services that relates to K-12 schools and their surrounding areas. This might involve reviewing existing literature and research, consulting with experts, and gathering input from stakeholders such as educators, students, and community members.

2. Gathering Data: Once the relevant ecosystem services have been well defined, we would collect necessary data to assess the distribution and quality of those services. This might involve a combination of aerial or satellite imagery, available datasets, and possibly some fieldwork such as site visits and surveys.

3. Analyzing Data: Once the data have been collected,we could analyze it to identify patterns and trends in the distribution and quality of ecosystem services. This might involve statistical analysis, geometric calculation, spatial analysis, and/or other analytical techniques.

4. Provide Result and Conduct Conclusion: Once the data have been analyzed, we could hopefully conduct some meaningful conclusions and provide useful data to the stakeholder. Potential conclutions include the quality of ecosystem services, disparities in the distribution, and significant trends. We would also process the output of our findins to any necessary format (database in our case) that could be useful for the stakeholders.


### D. Outline a path to operationalization.

The expected final deliveriable for this project is a database of greenness ES for all K-12 schools in Boston and Chelsea. We could deploy a database on a web service provider (such as AWS or Google Cloud) and provide APIs as well as simple web user interface for querying the data by given constrains. We could also implement and provide access to an Online Analytic Processing (OLAP) system that aggregate both real-time data (such as real-time weather map) and our processed data in a meaningful way. In order to archive high availability, we could apply tools and/or services from the web service provider. Some potential tools are: monitor, alarms, auto-scaling, and load-balancer.


## Resources


### Data Sets
* [K-12 schools in US](https://nces.ed.gov/programs/edge/geographic/schoollocations)
* Google Earth
* Google StreetView or use API using list of schools
* [Landsat (NDVI & EVI)](https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LC08_C01_T1_8DAY_EVI)
* [Tree canopy](https://data.fs.usda.gov/geodata/rastergateway/treecanopycover/)
* CDC Social Vulnerability Index & other disparity databases 
* [Mapping inequality redlining maps](https://www.atsdr.cdc.gov/placeandhealth/svi/index.html)
* [Air pollution (PM2.5)](https://beta.sedac.ciesin.columbia.edu/data/set/aqdh-pm2-5-concentrations-contiguous-us-1-km-2000-2016)
* [Land surface temperature](https://www.usgs.gov/landsat-missions/landsat-collection-2-surface-temperature) 

### References

<<<<<<< HEAD
=======
1. 
>>>>>>> 73a8ba81c5222f60220a2f930b17b6b58955502b

## Weekly Meeting Updates

Access our team weekly meeting notes [here](https://docs.google.com/document/d/1HQDMZKpkiLygbhWLCOMG4iaCj2k0TzJtZsnc8XFbgL4/edit#). 



# DC Crime Prediction
A team repo  for  project 5 for Client with The Lab @ DC (GA-DSI)

# Settings
  1) Make sure you have `.gitignore` in your local repo by adding this line: `input/csr/*`
  2. Download  with out forking so that we can work and push on things we have done
  3) Make sure you install and track Git Large File Storage(read more: https://git-lfs.github.com)
    - `git lfs install`, `git lfs track "*.csv"`
    - this will create  `.gitattributes` in your local repository.

# Approaches
pproaches and Deliverables with DC crime Prediction 
**Approach** 
   - Determine which variables provide the highest correlation with crime incidents 
   - Visualize incidents in a map for different choices of variables and filters 
   - Heatmaps, kernel density estimate plots to correlate variables 
**Feature selection**
 - Time series analysis on variables 
  - Identify seasonal effects 
  - Determine anomalies 
  **Prediction models** 
   Regression (to determine the evolution of patterns over time) Clustering (to determine common patterns across census tracts, Wards or ANC, etc.) Classification (to predict if a given crime is likely to happen in a given time and location) 
  **Deliverables**
  -  A notebook including: Analysis of crime patterns Models for predicting crime
----------------------------------------------------
# Sources: datasets
  1) Open Data DC
    - https://opendata.dc.gov/datasets/camera-enforcement-locations
    -  https://opendata.dc.gov/datasets/traffic-camera
    - https://www.arcgis.com/home/webmap/viewer.html?webmap=c88bff76cd3e4568800a19e9f361822e
    - https://opendata.dc.gov/datasets/crime-incidents-in-2017/data
    - https://opendata.dc.gov/datasets/crime-incidents-in-2016
    - https://opendata.dc.gov/datasets/crime-incidents-in-2015
    - https://opendata.dc.gov/datasets/crime-incidents-in-2014
    - https://opendata.dc.gov/datasets/crime-incidents-in-2013
    - https://opendata.dc.gov/datasets/crime-incidents-in-2012
    - http://opendata.dc.gov/datasets/real-property-tax-assessment-neighborhoods 
    - http://opendata.dc.gov/datasets/real-property-tax-assessment-sub-neighborhoods
    - https://mpdc.dc.gov/publication/shotspotter-data-disclaimer-and-dictionary
    - https://opendata.dc.gov/datasets/specialty-lighting


    - fetched, June, 2018

  2) City Service Requests Data, Open Data DC
  http://opendata.dc.gov/datasets?q=service%20requests
    http://opendata.dc.gov/

    - 2014: http://opendata.dc.gov/datasets/city-service-requests-in-2014
    - 2015: http://opendata.dc.gov/datasets/city-service-requests-in-2015
    - 2016: http://opendata.dc.gov/datasets/city-service-requests-in-2016
    - 2017: http://opendata.dc.gov/datasets/city-service-requests-in-2017
    - fetched, June, 2018
### Team
Client project teams !

| Team  Members |
|--------|
| Awab   | 
| James  |  
| Kiros  |
| Eric   |
|        |      


#### Additional from the Project lab
---------------------------------
### Problem Areas, Potential Questions, and Additional Resources

In consultation with the Lab @ DC, we've organized questions into three main problem areas.  You are not limited to addressing these questions, but they are some of the questions that are currently of interest to The Lab!
____________
### Problem Areas

- **Crime-Related**:
  - Does crime go up when street lights go out? (This is actually an open data science project that The Lab is working on right now, led by a volunteer. You can check out the repo [here](https://github.com/thelabdc/lights-and-crime). You could pick up an existing thread or start from the ground up!)
  - Can we predict how many people are going to be in jail or released from jail? Are there issues associated with this, such as overcrowding? Are there (evidence-based) steps that could be taken to avoid some of these issues?
  - Do wireless hotspots or security cameras reduce crime?
  - If we built similar models to predict gunshots and to predict 311 calls (using the same predictors, say) what might we learn from comparing the model parameters and predictions?
  - Using [this](https://github.com/thelabdc/NEAR-Act-Public) data:
    - Can we tell if being charged with one crime is highly predictive of also being charged with certain other crimes, or: 
    - Are there other factors that predict a combination of offenses (e.g. maybe arrests in specific locations are more likely to have specific combinations of charges)
  - DC makes available [crime incident location data](http://opendata.dc.gov/datasets/crime-incidents-in-2017). Using that data:
    - Can you build a model to predict or explain crime? (Note: you can use continuously update [2018 Data](http://opendata.dc.gov/datasets/crime-incidents-in-2018) as a real-life test set.)
    - Can you merge this dataset with another dataset to explore the relationship between crime and, e.g. house prices, parking tickets, 311 requests, or certain city infrastruture?

- **Property-Related**:
  - Can you identify different features from an [aerial image](http://opendata.dc.gov/pages/dc-from-above) in order to predict whether a house is vacant, or identify the type of property?
  - Using [Real Property Values](http://opendata.dc.gov/datasets?q=real%20property):
    - Can you estimate or assess housing values based on aerial imagery, voter file data, and other information?
    - Can we make inferences about property values or demographic trends given construction and occupancy permits?

- **Forecasting**:
  - Can we forecast service needs around DC based on [311 service calls](http://opendata.dc.gov/datasets?q=service%20requests) and other data?
  - Can we forecast [traffic accidents, moving violations, and parking tickets](http://opendata.dc.gov/datasets?q=parking%20violations&sort=-updatedAt)? Based on these forecasts, can we make policy recommendations, forecast revenue, or 
  - Can we build a voter turnout model to predict the likelihood that someone will vote. Data data are available from the Board of Elections for $5 on a CD. If you build the model before the June primary, you’ll have a built-in test set!

_____________

### Additional Resources
The [DC Open Data Portal](https://opendata.dc.gov/) is your friend.
______________

The [DC FOIA Reading Room](https://foia-dc.gov/App/ReadingRoom.aspx) gives access to documents released under the Freedom of Information Act.

___________

[The DC Policy Center](https://www.dcpolicycenter.org/) releases a lot of reports that may be of interest, including:
  - [Taking Stock of the District's Housing Stock](https://www.dcpolicycenter.org/publications/taking-stock-full-report/), with data available.
  -  [Can Neighborhood Characteristics Explain Enrollment in at In-Boundary Schools?](https://www.dcpolicycenter.org/publications/schools-in-the-neighborhood-summary/), with data from the Deputy Mayor for Education.

_____________

The [Federal Government's data portal](https://catalog.data.gov/dataset) may provide some interesting data to cross refence against.
This is a project I was tasked with while at the QA Consulting IT training academy. The idea was that using the Iowa Homes dataset to produce a machine learning model with which to predict the house prices of new entries into the data set. Then once completed this project was to be uploaded onto the cloud so as to be easily acessible at any time. To view the completed version of this project you can visit http://34.89.15.145/

The technologies used in this project were R and R Shiny for the backend and user interface of the project, as well as Google Cloud Platform for hosting online, and an SQL database to store the data to train the model. The model specifically used to predict house prices was KKNN, or the weighted k nearest neighbour algorithm. After cleaning the raw data to a point where I had enough usable and useful information about all the houses, I managed to use this algorithm to predict new house prices to within around 10%. 

In future sprints I would aim to increase the usability of the website, as although fully functional it definitely could be improved on. I would also like to play around more with different parts of the dataset to see if the predictions could be improved even further under KKNN. Additionally it would be useful to be able to predict prices even if one or more fields were null or undocumented, and further these fields could be predicted using the KKNN algorithms. 

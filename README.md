# Credit Scoring System Integrated with Alibaba International Tech Stack by Nexus Solutions
## Workflow
We, Nexus Solutions, designed a system which calculates seller credit standings based on hundreds of seller attributes. We employed a LightGBM regression model and performed hyperparameter tuning and bootstrap aggregating using methods from the pyCaret Python library, achieving an R-squared score of 95% on unseen test data (20% of initial dataset). Using the sklearn2pmml API, we converted the finalized and trained model to a pmml file format which allows our model to be directly integrated to Java programming language. Once the Java pmml file is obtained and necessary dependencies are installed on the Java environment, Alibaba International can evaluate and run the model alongside their existing technologies

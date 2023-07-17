# SpaceX-Extracting Insights From Launch Data & Predicting Stage One Landing Success - A ML Approach
Project Background and Context:​

Objective: Predict the successful landing of Falcon 9 first stage rockets.​

Importance: Cost optimization in rocket launches, with SpaceX's Stage 1 reusability feature leading to significant savings​

Problems to Find Answers:​

Cost Comparison: Understand how SpaceX saves money through reusability, offering launches at $62 million compared to competitors' costs of $165 million.​

Landing Success: Determine factors that contribute to successful landings and identify reasons behind unsuccessful landings.​

Cost Estimation: Utilize machine learning models to predict the success or failure of Falcon 9 first stage landings, and leverage these predictions to estimate the cost of a launch 

----------------------------------------------------------------------------------------------------------------------------------------------------------

Data collection:

- Interacting with SpaceX API's​

- Web-Scraping a SpaceX Wikipedia Table using Beautiful Soup ​

Data wrangling​:

- One hot encoding data fields for Machine Learning, Handling Missing Values, Dropping Irrelevant Columns, Data Formatting & Data Types, Constructing the Landing Success Column (Output)​

Conduct (EDA) Exploratory data analysis using:
- Visualization Libraries (Seaborn, Matplotlib, etc.)
- SQL​

Create interactive visual analytics:
- Interactive Folium Maps - https://nbviewer.org/github/AsimAShah/SpaceX-Data-Science-Capstone-Project/blob/Main-Branch/Interactive%20Folium%20Maps%20using%20Launch%20Data%20%28Geospatial%20Analysis%29.ipynb
- Interactive Dash App using Plotly - https://spacexinteractdash-47f4873d7069.herokuapp.com/
- Tableau Interactive Dashboard Story - https://public.tableau.com/app/profile/asim.shah5745/viz/SpaceXStageOneLandingFactorsSuccessRates/Story1?publish=yes

Perform predictive analysis using classification models​:
- Perform Feature Scaling​, build and train Logistic Regression, SVM, Decision Tree, and K-Nearest Neighbors Classification models using the optimal hyperparameters and the number of folds for Cross Validation. Finally, use evaluation metrics to see how well the models perform on training data and generalize to the unseen test data


Final Report (PowerPoint PDF) - https://github.com/AsimAShah/SpaceX-Data-Science-Capstone-Project/blob/Main-Branch/Final%20Report%20Powerpoint.pdf

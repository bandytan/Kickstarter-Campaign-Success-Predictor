# About Kickstarter Campaign Success Predictor 

## What is crowdfunding? 
Crowdfunding is an increasingly popular means to help individuals and businesses raise funds to realise their projects. Fundraising campaigns are typically initiated on crowdfunding platforms like Kickstarter, and backers can pledge money towards campaigns. Backers prefer campaigns to succeed (Kickstarter, n.d.), as they want to receive rewards from successful campaigns (Mikhaylova, n.d.). 


## The Problem 
Backers may not know how likely a campaign is to succeed in the future - much time has to be spent doing due diligence of ongoing campaigns. If they eventually back a failed project, they will have wasted their time, and face disappointment from not getting the rewards that they had wanted. Machine learning could solve this issue - there are findings relating a campaign’s success to its linguistic style (Parhankangas & Renko, 2017), but have yet to be fully implemented. Currently, tools like BackerKit can give projections of pledged amounts based on past similar projects, but it does not incorporate the nuances of textual data. 

## Our Solution 
Thus, we aim to use machine learning to predict the success of campaigns for backers to maximise the net return on investments, and to minimise the opportunity cost of their investments.

# Introduction To Codes 
1.  Scraping GraphQL.ipynb 
    - Example code on how we scraped Kickstarter Story and Risks 
    - Not advisable to run on full webrobots dataset as it will take weeks 
2. Data Collection Pipeline.ipynb
    - Code to combine all datasets
3. Data Cleaning.ipynb 
    - 4-step cleaning process to clean output produced after merging datasets in Data Collection Pipeline.ipynb
4. Feature Engineering.ipynb
    - Feature engineering based on cleaned dataset in Data Cleaning.ipynb
5. All notebooks in /models 
    - Each notebook contains code that trains different ML models and evaluate performance
6. Visualisations.ipynb
    - After tuning all models to obtains optimal hyperparameters, training them again here to compare all models  
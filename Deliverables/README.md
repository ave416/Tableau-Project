# Final-Project-Tableau

## Project/Goals
- Identify trends within the provided dataset using tableau and data visualizations
- From those visualizations, attempt to answer questions about the burden of TB for different countries

## Process
### 1. Planning
- This step consisted strategizing the approach to the project
- Planning out explicit steps allowed for better time management, and also a more structured approach to the analysis
### 2. Data Exploration
- Before dashboards could be finalized, it was important to have a strong understanding of the data set
- Identifying areas that might need cleaning
- Identifying outliers and deciding on actions to take
- Using simple visualizations to see how the different variables interacted with one another
### 3. Creating a Story
- Next was the goal of creating a data visualization story
- The challenge was in creating visualizations and worksheets to cover the most important features of the data, while also ensuring it could be summarized within a 5 minute presentation
- Thinking about the audience was also an important factor
    - Understanding the audience allowed for certain redundant information to be left out of both the visualizations, or for some background information to be provided
- It was import to think about which visualizations would smplify the trends, without introducing biases, while also being easy to interpret

### 4. Finalizing the Story
- Finalizing the finishing aesthetic touches on the story
- Looking to create an aesthetic that compliments the information without distracting from it
- Creating a presentation script that feels engaging to the audience while considering time constraints

## Results
(Fill in which Option you chose, either 1 or 2. List the dataset you selected for the project if you selected Option 2. Also, discuss the visualizations you created, and why. For Option 2, also identify what your data question was, and how you went through the prompts.)
- Option 2 with the dataset TB_Burden_Country was chosen
- As this data focused on the burden per country, maps were very useful
    - A shaded map chart was used on a number of occasions, both to relay information but also to add interesting visuals to the presentation
- Bar graphs with filters, or rankings were used to demonstrate which countries were the most burdened, and also to identify the data skew as a result of population
- To indicate which regions were most burdened, bar graphs with average lines, and regional average lines were used, alongside a map to highlight the countries within a region
- Line charts were used to demonstrate changes over time
    - From these charts were were able to identify broad regional trends, that implied the fight against TB is in fact a winning battle, as the lines were all trending towards lower case counts and deaths
- Scatter plots were used to identify outliers as well, and also show how different countries could be clustered
    - In the clustering, the clusters ended up grouping by high HIV-TB infection rates, high mortality rates, and high overall case counts
- A scatter plot with a trend line that had an R-squared value of 0.94 shows a very strong correlation between mortality and HIV positive TB patients
- Similar graphs, either changing or plotted over time were used to identify that despite the strife caused by TB, we are in fact trending towards less deaths, and lower case counts. 

- The main question about the data was whether or not we could identify the most heavily burdened regions or countries
- It seemed clear from the results that the most heavily burdened region is Africa, with SE Asia in a close second
- The first step was ensuring that we were comparing normalized data
    - Comparing case count in China or India for example did not make sense. Due to their large populations, they naturally had higher case counts, but the burden's on those countries were lower due to their greater resources (larger population)

## Challenges 
- One challenge with the project was deciding on visualizations to use to tell the story.
- There are many small details in a data presentation can have large effects on the audiences experience. 
- As there was so much information within the data set, it was difficult to limit the content in the presentation in order to fit the time slot
- Not having previous knowledge about TB also proved a bit of a challenge as it required some additional background research to be done before completing the project

## Future Goals
- With more time, a deeper dive into specific countries could be completed
    - This could help to identify the most burdened countries and potentially identify some trends that could be driving their high prevalence
- With additional data, more conclusions could be drawn about the prevlaence of TB throughout the world
    - There were no socioeconomic factors in the dataset, which can often have a large impact on the ability of a region to deal with a global health crisis. 
- Another future improvement that could be made to the dashboard, would be to create a dynamically sized dashboard, and one that is meant to be interacted with by a user, rather than demonstrated in a presentation

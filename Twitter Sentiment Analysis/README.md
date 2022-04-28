## Regression Analysis and Twitter Sentiment Analysis
### Regression Analysis:

I did Regression Analysis on two different dataset with different models.

### Player-Centric Time-based Sentiment Tracking and Prediction From Twitter Data.

Given tweets data on Superbowl 49, patriots and hawks hashtags, I tried to answer following questions:

For each fan group, can we track the average perceived emotion in the tweets about each player across time during the game?
Can we correlate these emotions with the game score in the given time interval?
Given the tweets emotions about some players for 1 minutee interval can we predict who is winning the game?


#### Instructions to Run the Code

There are 3 separate notebooks:
- Project_4_Part1_Regression_Analysis.ipynb: Part 1 notebook
- Project_4_Part2_Twitter_Data.ipynb: Part 2 main notebook
- P4_Roberta.ipynb: For Roberta Sentiment Features code in Part 2

How to run the notebooks:

On Colab:
- You can directly run the notebook on Colab or in local. 

On your local environment:

2. To Run the solution from your own local environment you can create a conda environment:

    2.0. Inside environment.yml, change the prefix in the last line to the path you want to save your environment. You can put any path or at least change the 
    "/Users/user_name/opt/anaconda3/envs/ece219_p4" username part.

	2.1. Create conda environment using the given environment.yml file    
	`conda env create -f environment.yml`

	2.2. Activate the conda environment   
	`conda activate ece219_p4`

	2.3. In your terminal run the following to be able to see your environment as kernel in jupyter  
	`python -m ipykernel install --user --name=ece219_p4`

	2.4. Open jupyter lab from terminal   
	`jupyter lab`

	2.5. Open Project1_solutions.ipynb, go to Kernel -> change kernel -> select 'ece219_p4'

	2.6. Run all cells: 
	- Run -> run all or
	- Kernel -> restart kernel and run all



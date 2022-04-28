
### Movie Recommender System

I built and evaluated different recommendation models (KNN, NMF, MF and naive approaches) to predict the ratings of movies. 
MovieLens dataset is used.

#### Instructions to run the project_3.ipynb notebook

On Colab:
- You can directly run the notebook on Colab. you need to download surprise library to the environment first !pip install scikit-surprise.
- You neeed to als upload the dataset on the environment.

On your local environment:

2. To Run the solution from your own local environment you can create a conda environment:

    2.0. Inside environment.yml, change the prefix in the last line to the path you want to save your environment. You can put any path or at least change the 
    "/Users/user_name/opt/anaconda3/envs/ece219_p3" username part.

	2.1. Create conda environment using the given environment.yml file    
	`conda env create -f environment.yml`

	2.2. Activate the conda environment   
	`conda activate ece219_p3`

	2.3. In your terminal run the following to be able to see your environment as kernel in jupyter  
	`python -m ipykernel install --user --name=ece219_p3`

	2.4. Open jupyter lab from terminal   
	`jupyter lab`

	2.5. Open Project1_solutions.ipynb, go to Kernel -> change kernel -> select 'ece219_p3'

	2.6. Run all cells: 
	- Run -> run all or
	- Kernel -> restart kernel and run all


environment.yml file contains all the package information with their versions.
Main Packages needed:

	jupyterlab==3.2.9
	ipykernel==6.9.0
	pandas==1.1.3
	matplotlib==3.5.1
	scikit-learn==1.0.2
	seaborn==0.11.2
	scikit-surprise==1.1.1

# Managing the end-to-end machine learning lifecycle with MLFlow

This Repository contains the resources for basic tutorial on MLFlow.

# Basic setup

## Setup the environment
- clone this repository
- **with virtualenv (recommended)**
  - create a new environment: `conda create -n  mlflow`
  - activate the environment: `conda activate mlflow`
  - run `pip install -r requirements.txt`

## The notebook
- Get the `hands_on_example.ipynb`
- run `jupyter notebook`
![image](https://github.com/sharad-TA/MLFlow_walkthrough/assets/104362558/5c813c5a-e24b-440d-871b-40ed1c0e5acc)

- Go to the server and start executing the cells in the Notebook 
![image](https://github.com/sharad-TA/MLFlow_walkthrough/assets/104362558/4375c90d-4314-4a91-8146-590bb8ac36da)

## Setting up MLFlow server

1. While Running the Jupyter Notebook as mentioned above, open a new console and activate the same Environment used by jupyter.
2. Run the following command
   - `mlflow ui`

     ![image](https://github.com/sharad-TA/MLFlow_walkthrough/assets/104362558/bbfd3788-9f83-495e-a9e7-5d579d493775)

3. Continue executing the rest of the cells in the Jupyter notebook and once done, go to the MLFlow UI 

## Final ML Flow UI
- This is the final MLFlow UI where we can track the different experiments
![image](https://github.com/sharad-TA/MLFlow_walkthrough/assets/104362558/e051a92c-e9cf-4c16-b1d8-30888e90f135)


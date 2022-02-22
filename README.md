# projects_supply_chain_data_analysis

# Table of Contents
1. [Supply chain data analysis](#supply-chain-data-analysis)
2. [Using this repository](#using-this-repository)
3. [Installation and configuration](#installation-and-configuration)



# Supply Chain Data Analysis

This project aims to use python, pandas and visualization libraries (matplotlib, seaborn, squarify, plotly) in order to 
develop a data analysis over a supply chain dataset. 

This project is divided in five tasks:

- Task 1. Initial Exploration
  * task1_initial_exploration.ipynb

- Task 2. Univariate & Multivariate Analysis  
    Due to the extent of the dataset this task will divided in subgroups of analysis. This subgroups are topics
    with common variables that focus on different elements of the supply chain. The topics are:  
     * Product  
       * product\task2_product.ipynb  
     * Customer  
       * customer\task2_customer.ipynb  
     * Stores  
       * stores\task2_stores.ipynb  
     * Shipping  
       * shipping\task2_shipping.ipynb  
     * Orders  
       * orders\task2_orders.ipynb  


- Task 3. Duplicates and missing values 
    * task3_dup_missval.ipynb

- Task 4. Correlation
    * task4_correlation.ipynb

- Task 5. Quality of the dataset
    * task5_dataset_quality.ipynb



## Using this repository

You can use this repository in the following way:  

1. Use github as a viewer to observe the analysis with ```.ipynb``` extension. You don't need to have Jupyter Notebook 
installed. To proceed with this option just click on the ```.ipynb``` file you want to open. 

2. Run this repository locally. To achieve this you will need to have Python and Jupyter installed.
    * Clone the repository
    * To run the queries open the following files in Jupyter Notebook
      ```
      task1_initial_exploration.ipynb
      product\task2_product.ipynb
      customer\task2_customer.ipynb
      stores\task2_stores.ipynb
      shipping\task2_shipping.ipynb
      orders\task2_orders.ipynb
      task3_dup_missval.ipynb
      task4_correlation.ipynb
      task5_validation_dataset.ipynb
      ```
  
## Installation and configuration
To run the scripts locally you will need to have installed:

* Python v.3.x.x
* Libraries
    * pandas:1.1.3
    * numpy:1.19.2
    * matplotlib:3.3.2
    * seaborn:0.11.0
    * squarify:0.4.3
    * plotly:5.5.0
* Jupyter Notebook

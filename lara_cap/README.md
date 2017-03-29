# Machine Lerning Engineer Nanodegree
## Unsupervised Learning

## Project: Clusters by use of time
 
 With Machine Learning we have the possibilities to include more information about people that might result in us discovering hidden patterns we weren't able to see before. We could perhaps add more meaningful information to simple demographics.   In this project I wanted to see if I could create simplified labels used in research to give a better understanding about the participants based on how they spend the 1,440 minutes that are in the day. I used the American Time Use Survey (ATUS) that measures how people divide their time among life’s activities. This survey includes more than just information about time use, where questionnaires have been added (Eating & Health Module, Well-Being Module, Eldercare Module) and participants have already participated in the Current Population Survey (CPS).   For further information you can download the Project report [here](https://www.dropbox.com/s/s9jvtr5zs2wk9d8/Project%20report.pdf?dl=0 "Dropbox link to Project report") 
 
### Install
This project requiers**Python 2.7** and the following Python libraries installed:
* Numpy
* Pandas
* Scikit-learn
* Pylab
* Matplotlib
* Seaborn
* Plotly

You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.

## Code
Template code is provided in the `the_clusters.ipynb` notebook file and the `data_basic_vis.ipynb` describes the data visually. You will also be required to use the `the_data.csv`and `big_data.csv` dataset files to complete your work. The `atus_data_cleanup.ipynb` was used to clean up, rename and manually merge some data. 

## Run
In a terminal or command window, navigate to the top-level project directory `lara_cap` (that contains this README) and run one of the following commands:

ipython notebook ´the_clusters.ipynb´
or

jupyter notebook `the_clusters.ipynb`
This will open the Jupyter Notebook software and project file in your browser.


## Data
In the `atus_data_cleanup.ipynb` was used to clearn, merge and rename columns within the ATUS dataset. When downloading the dataset from the web page (https://www.bls.gov/tus/) it came as .dat format. I converted the .dat to .xlsx2 and used `xlsx2csv.ipynb` to convert it to the csv file `data.csv` to be able to use it in ipynb. 

Here are links to the data needed for the project:
[data.csv](https://www.dropbox.com/s/z8mn8i31qoeldf5/data.csv?dl=0 "Dropbox link to data.csv")  
[big_data.csv](https://www.dropbox.com/s/t40kizyxe6h9sw9/big_data.csv?dl=0 "Dropbox link to big_data.csv")  
[the_data.csv](https://www.dropbox.com/s/0pieiwekby8lktm/the_data.csv?dl=0 "Dropbox link to the_data.csv")  
[s10big_data.csv](https://www.dropbox.com/s/z18s0zhnk9seklb/s10big_data.csv?dl=0 "Dropbox link to s10big_data.csv")  
[s10the_data.csv](https://www.dropbox.com/s/gid6bv8cqddl6vk/s10_the_data.csv?dl=0 "Dropbox link to s10the_data.csv")  


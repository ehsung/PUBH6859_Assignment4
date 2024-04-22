# PUBH6859 - Assignment 4

## Problem 1 Locations:
* Python Notebook:
  * https://colab.research.google.com/drive/1kY2yvWehpnQc_9d6YJveHXtOOBDspb9L?usp=sharing
* Google Drive Data:
  * https://drive.google.com/file/d/1-ThgtXtpFlHyxIBgLn6MWWAhWZ5TRjYo/view?usp=drive_link 

## Problem 1:
1. Go to PubMed_Visualization.ipynb github link.
  * https://github.com/omicsEye/pubSight/blob/main/notebook/PubMed_Visualization.ipynb 
2. Can fork over the git repo to open and modify, but I instead downloaded the notebook and uploaded it into my own personal google colab account.
  * Renamed it as: PubMed_Visualization__EHS_Modified.ipynb
3.	Go to: https://pubmed.ncbi.nlm.nih.gov/
  * Under the search bar, click Advanced
  * Following the table below:
    * Type in Main Term
    * Press ADD button
    * Type in AND Sub-Term
    * Press ADD button
    * Press Search
    * Under Results by Year, move slider to be from 1990 to 2024
    * Download the csv using the download button
    * Rename as: GROUPNAME(underline)SUBGROUPNAME.csv as instructed in notebook
    * Save to a folder in google drive
    * Repeat for all rows in the table.
4.	In the python notebook, run the code:
  * Mount my google drive
  * Change: drive_path to be: drive_path = ‘/content/drive/MyDrive/PUBH6859_Assignment4/'
  * Notebook will create png and pdf graphics of the charts
  * 

## Problem 2:
* pubh6859_assignment4_boto3_create.py
* pubh6859_assignment4_boto3_delete.py
* Confirmed the scripts works using the AWS site to see it being made and deleted
![image](https://github.com/ehsung/PUBH6859_Assignment4/assets/11777528/c06e71b3-500a-4ba4-9f8f-ddf28eb30d7c)

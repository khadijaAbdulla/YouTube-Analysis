# YouTube-Analysis
Youtube DataSet analysis - using python

### Project Title: 
Youtube Dataset Analysis
### Overview:
This project analyzes the data for Great Britain's Trending Youtube videos, and Analysing what factors affect how popular a YouTube video will be. 
Engagement in GB YouTube trending videos is mainly driven by specific categories , while other categories show weak or stagnant interaction. This imbalance suggests limited audience diversity and declining interest in non-entertainment content.
### Information about the DataSet:
- Name: Trending YouTube Video Statistics (GB)
- Source: [https://www.kaggle.com/datasets/datasnaek/youtube-new/data](url)
- Original Data Source: [https://github.com/DataSnaek/Trending-YouTube-Scraper](url)
- Size: 38,916 Rows - 15 Columns
### Key Findings:
- Music dominates in both views and engagement, confirming its leading role in GB’s trending content.
- Weekend uploads, especially in Music and Entertainment, gain slightly higher engagement. 
- Likes and comments are strongly correlated, reflecting positive audience interaction.
- Blend entertainment with other genres to attract more audiences.
- Use weekend spikes to launch interactive campaigns. 
### How to Run:
1. Donwload the whole repository.
2. Access the Dataset Link from the Source link and Download the dataset CSV file from Kaggle.
3. Unzip the dataset file and make sure that it is in the same file location as the python file. 
4. Open the python file using Jupyter Notebook/Jupyter Lab. For the installation instructions kindly follow the steps mentioned in the official documentaion [https://jupyter.org/install](url)
5. Make sure to install any depenedcies(mentioned below) before running the code e.g. Pip install dependency-name.
6. Run the full python code by navigating to the **Run** menu and click **Run All cells**.
### Dependencies:
- pandas
- json
- numpy
- re
- matplotlib.pyplot
- seaborn
- matplotlib.ticker
### Troubleshooting:
##### FAQ1: Cannot locate the Dataset's CSV file:
The file can be downloaded from the **Source** link provided above in the **Information about the DataSet** section. Access the link > Click on the **Download** button > Select **Download dataset as zip** > **Decompress** the downloaded file > Make sure that the "GBVideos.csv" file is moved to the project folder along with the python file. 

#### FAQ2: I have Python installed, but my complier does not recongize one of the dependencies when I run the porject file. 
This means that you need to install the library so that it is recognize by the complier. 
Add an extra cell to the python file with the following command: 
**pip install dependency-name**
Example:
**pip install numpy**
Please make sure to run all the code again after the dependency installation.

***Kindly contact us via email for any additional support KhadijaAbdullaA@gmail.com,-other emails-***

### Limitations & Future Work:
Since the YouTube algorithm changes over time and this dataset is limited to two years only(2007-2018), if we had more recent data, we could compare between the factors that effect the how popular a video is over the years.

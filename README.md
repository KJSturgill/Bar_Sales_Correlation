# Bar_Sales_Correlation
## A project meant to show correlation between events and what is selling at a bar. (mock sales data used)

This project was intended to show correlations between events, both at the bar and locally, and drink sales, in an effort to offer a better plan for ordering supply, and to not run out as often. As I started working with the data to build the project, I was asked to no longer use the data in a public setting. This project was for a coding class, so I needed it to be public. I had considered finding a new topic and data for this project, but nothing called to me the way data I've been wokring with for nearly a decade did, and building the framework to make visualizing patterns in sales here is something that benefits me in the real world even if I cant post the real data on this project. So I set out to restart the same project from scratch, just using mock data. I kept the calendar roughly the same, shedding a few events and details that belong to the company, throwing generic things in place of named things. I also cut out the weather tied to the calendar, as theres no good way to use the mock data to show anything with that correlation. I then used a number generator to build a years worth of fake sales to plug into the datasets. The generated data fits roughly along the paths I wanted to demonstrate, with minor touchups here and there to have something to demonstrate possible correlations to events.


## Requirements for Code:You
1) Read TWO data files (JSON, CSV, Excel, etc.).
2) Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set.
3) Make a Tableau dashboard to display your data.
4) Utilize a virtual environment and include instructions in your README on how the user should set one up.
5) Annotate your code with markdown cells in Jupyter Notebook, write clear code comments, and have a well-written README.md. Tidy up your notebook, and make sure you don’t have any empty cells or incomplete cells that don’t do anything. Make sure it’s all functional before your final github commit.


## Instructions
1) Clone my Repo to your machine 
`git clone https://github.com/KJSturgill/Bar_Sales_Correlation.git`

2) After you have cloned the repo to your machine, navigate to the project 
folder in GitBash/Terminal.

Virtual Environment Commands
| Command | Linux/Mac | GitBash |
| ------- | --------- | ------- |
| Create | `python3 -m venv venv` | `python -m venv venv` |
| Activate | `source venv/bin/activate` | `source venv/Scripts/activate` |
| Install | `pip install -r requirements.txt` | `pip install -r requirements.txt` |
| Deactivate | `deactivate` | `deactivate` |

3) Open `Dataframe-Notebook.ipynb` and run all cells. This notebook merges and cleans the data, sorting it into dataframes to show correlations, with notes to explaine how and why in terms my fiance with no code experienc can read.

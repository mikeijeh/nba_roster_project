# NBA Roster Evaluation Project

<span style='color:#49df98'>**NBA Roster Evaluation Data Science Project**</span> -- This repo includes the NBA Roster Evaluation library <span style='color:#49df98'>**nba_roster_project**</span>.

The motivation for this project is to apply a "portfolio management" lens to analyzing what factors contribute to both winning and player salaries. This project also serves as my first self-initiated project, applying knowledge and ideas from my career as an institutional investor to the NBA.

If you would like to run the same environment I ran to generate the outputs/code, please run the following command in the command line:

* `conda env create -f environment.yml`

The NBA Roster Evaluation Project first utilizes data from basketball-reference.com and ESPN.com. The salary cap data came from erikgrogorywebb's Github (https://github.com/erikgregorywebb/datasets/blob/master/nba-salaries.csv).

There is one notebook and one Excel file in <span style='color:#49df98'>**nba_roster_project**</span> to be aware of:

* `NBA Roster Evaluation Project.ipynb` - This is the primary notebook where the analysis sits. The project addresses three topics that are connected to investing in the stock market:

1. Identifying the advanced statistics that drive the "market inefficiencies" in how players are paid vs. how they contribute to winning;
2. Narrow down the factors that drive a player salaries and use those to find the "intrinsic value" of a player; and
3. Separate the "alpha" from the "beta" for a player's win production.

* `NBA DCF model.xlsx` - This is the file needed to calculate the "intrinsic value" of a player. You will need to download the raw file to utilize it, as well as have basketball-reference.com available for the needed inputs.

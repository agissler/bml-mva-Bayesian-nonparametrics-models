# Bayesian Machine Learning Report 2019-2020
# Bayesian non-parametric models for ranked data

We can find the paper which this project is based on in the master repository.

In this repository, there is a Jupyter Notebook where there are our experiments. If you want to run it, you have to download it, and download the content of the data repository in the same folder.

The first experiment learns with Gibbs sampler the weights associated to Golden Ball players according to the African vote 2019. 
Here are the mean of the weight for each player and their distribution given by the algorithm.

![Mean of scores](/report/mean_score_player.png)
![Distribution](/report/Distrib_player.png)



The second experiment learns the time-dependant weights associated to movies according to their rankings in box-office between October 2019 and February 2020 in four countries (France, US, UK and Germany). As it take some time to be executed, the number of iterations is set to 1000, but it would be more appropriate to run at least 10000 iterations.

Our personnal report is in the report repository.




Authors : Armand Gissler/Raymond Zhang

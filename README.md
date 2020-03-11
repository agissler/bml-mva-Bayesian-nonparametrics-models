# Bayesian Machine Learning Report 2019-2020
# Bayesian non-parametric models for ranked data

We can find the paper which this project is based on in the master repository.

In this repository, there is a Jupyter Notebook where there are our experiments. If you want to run it, you have to download it, and download the content of the data repository in the same folder.

The first experiment learns with Gibbs sampler the weights associated to Golden Ball players according to the African vote 2019. 
Here are the mean of the weights for each player and their distribution given by the algorithm.

![Mean of scores](/report/mean_score_player.png)
![Distribution](/report/Distrib_player.png)



The second experiment learns the time-dependant weights associated to movies according to their rankings in box-office between October 2019 and February 2020 in four countries (France, US, UK and Germany). As it take some time to be executed, the number of iterations is set to 1000, but it would be more appropriate to run at least 10000 iterations.
Here are the evolution of the weights of the movies throught time. Because there are a lot of movies, the plot are dispatch in 5 different figures.
We also add the plot of the $w^*_*$ the weight of objects not present in the rankings.

![score 1](/report/top5_box_office_usukfrde_results10000itev3_part1.png)
![score 2](/report/top5_box_office_usukfrde_results10000itev3_part2.png)
![score 3](/report/top5_box_office_usukfrde_results10000itev3_part3.png)
![score 4](/report/top5_box_office_usukfrde_results10000itev3_part4.png)
![score 5](/report/top5_box_office_usukfrde_results10000itev3_part5.png)
![Total score](/report/top5_box_office_usukfrde_results10000itev3_part6.png)

Our personnal report is in the report folder.


Authors : Armand Gissler/Raymond Zhang

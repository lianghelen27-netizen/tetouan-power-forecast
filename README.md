# tetouan-power-forecast
# **Can we predict Zone 1 demand one hour ahead, and how much better is a real model than just assuming demand repeats?**
This project predicts power comsumption in Tetouan, Morocco, one hour ahead, using 10-minute grid measurements from 2017. It compares linear regresson and random forest regressor prediction models to the baseline of assuming demand repeats. (same time yesterday)

# Results

linear regresson model had a MAE of 812.040 and an r^2 value of 0.969. The MAE is 19.4% lower than the one day baseline

Random forest regressor model has a MAE of 1153.854 and a r^2 of 0.939. The MAE 14.5% higher than the one day baseline

the one day baseline (one day ago) had a MAE of 1007.404 and a r^2 of 0.941

the persistence (load 1 hr ago) had a MAE of 1857.006 and a r^2 of 0.826

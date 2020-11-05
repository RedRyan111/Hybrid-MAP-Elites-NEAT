﻿# Hybrid-MAP-Elites-NEAT
Hybrid algorithm where both NEAT and MAP-Elites run respective model archives and crossover with each other. Models train on OpenAI gym's Bipedal-Walker environment. 

The two criteria that saved an agent onto the MAP-Elites were its average horizontal speed and the percentage of time both legs were on the ground. 

**HeatMap of average horizontal speed of agent vs  percentage of legs on the ground, with the saved reward on the z-axis**

MAP-Elites using NEAT mutation and crossover functions | Pure NEAT where MAP-Elites are saved | Hybrid where both algorithms interact together
------------ | ------------- | -------------
![](https://github.com/RedRyan111/Hybrid-MAP-Elites-NEAT/blob/main/Plots/MAP-Pure-saved-elites-w-weighted-graphs.png) | ![](https://github.com/RedRyan111/Hybrid-MAP-Elites-NEAT/blob/main/Plots/NEAT-Pure-fixed-saved-elites.png) | ![](https://github.com/RedRyan111/Hybrid-MAP-Elites-NEAT/blob/main/Plots/temp_try_elites.png)

**Plots of Average Reward vs Generation number**

MAP-Elites using NEAT mutation and crossover functions | Pure NEAT where MAP-Elites are saved | Hybrid where both algorithms interact together
------------ | ------------- | -------------
![](https://github.com/RedRyan111/Hybrid-MAP-Elites-NEAT/blob/main/Plots/MAP-Pure-saved-elites-w-weighted-graphs.png) | ![](https://github.com/RedRyan111/Hybrid-MAP-Elites-NEAT/blob/main/Plots/NEAT-Pure-fixed-saved-elites.png) | ![](https://github.com/RedRyan111/Hybrid-MAP-Elites-NEAT/blob/main/Plots/temp_try_elites.png)

**Plots of Highest Reward vs Generation number**

MAP-Elites using NEAT mutation and crossover functions | Pure NEAT where MAP-Elites are saved | Hybrid where both algorithms interact together
------------ | ------------- | -------------
![](https://github.com/RedRyan111/Hybrid-MAP-Elites-NEAT/blob/main/Plots/MAP-Pure-saved-elites-w-weighted-graphs.png) | ![](https://github.com/RedRyan111/Hybrid-MAP-Elites-NEAT/blob/main/Plots/NEAT-Pure-fixed-saved-elites.png) | ![](https://github.com/RedRyan111/Hybrid-MAP-Elites-NEAT/blob/main/Plots/temp_try_elites.png)

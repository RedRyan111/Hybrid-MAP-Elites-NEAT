# Hybrid-MAP-Elites-NEAT
Hybrid algorithm where both NEAT and MAP-Elites run respective model archives and crossover with each other. Models train on OpenAI gym's Bipedal-Walker environment. 

The two criteria that saved an agent onto the MAP-Elites were its average horizontal speed and the percentage of time both legs were on the ground. 

**MAP-Elites using NEAT mutation and crossover functions**


**Pure NEAT where MAP-Elites are saved**

**Hybrid of both algorithms where NEAT runs generation buffer that saves MAP-Elites and where MAP-Elites come back during crossover**

First Header | Second Header
------------ | -------------
![](https://github.com/RedRyan111/Hybrid-MAP-Elites-NEAT/blob/main/Plots/MAP-Pure-saved-elites-w-weighted-graphs.png) | ![](https://github.com/RedRyan111/Hybrid-MAP-Elites-NEAT/blob/main/Plots/MAP-Pure-saved-elites-w-weighted-graphs.png)

Pure NEAT | Pure MAP-Elites | Hybrid Algorithm
------------ | -------------
![](https://github.com/RedRyan111/Hybrid-MAP-Elites-NEAT/blob/main/Plots/MAP-Pure-saved-elites-w-weighted-graphs.png)  | ![](https://github.com/RedRyan111/Hybrid-MAP-Elites-NEAT/blob/main/Plots/MAP-Pure-saved-elites-w-weighted-graphs.png) | ![](https://github.com/RedRyan111/Hybrid-MAP-Elites-NEAT/blob/main/Plots/MAP-Pure-saved-elites-w-weighted-graphs.png)

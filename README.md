# 8QueensProblem
Used Evolutionary Algorithm to find the 8 queens problem. Population is initialized with a random unique number between 1 to 8.  High quality parents are selected for crossover. 
Here lower checks count is considered as high quality parent. We used Partially Mapped Crossover and Swap mutate. Once the children are created we add them with the parents and low quality  parents are removed from the list. Same  process is repeated unit we get a high quality ( number of checks zero ) or if its reaches 10k iterations 

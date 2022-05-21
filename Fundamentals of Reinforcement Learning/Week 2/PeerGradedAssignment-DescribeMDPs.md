Create an MDP. Remember to describe the states, actions and rewards. Make sure your three MDPs are different from each other.

1. My first MDP is a submarine that is searching underwater for caves, any type of exploration like new species,  ores and such.

States = {The amount of fuel and the air left in submarine, cameras to see under ocean,  Sonar}
Actions = {Search, Wait,  Ascending, Descending, Accelerate, Decelerate}
Rewards = {So the rewards can be like -1000000 for crashing the submarine (- a lot  in short term), maybe like +200 for exploring anything new and -1 for each time step so it will know what it is looking for}

2. The second MDP will be an aimbot.

States = {Keyboard, mouse movements and clicks, position of the cursor, location in map}
Actions = {click,move, stay and wait, aim, target, run}
Rewards = {This time, dying might end up with lower - reward like -100. Each moving step can be around -1 and killing an enemy in game will be +1 for body shots and +10 for headshots. This way, it will learn to kill with headshots}

3. Third and last MDP is Stock Management.

States = {Available inventory or stock in each period of time,  stock allocation, position of empty and allocated inventory spots}
Actions = {control, allocate, empty, search,  find, bring}
Rewards = {Every time it succesfully allocates or empties a slot, it can be rewarded with +50, waiting time steps will not cause any - reward because there is nothing to do at current moment. But to fasten things up when we need to bring an item, we can put -1 reward for each time step. Failing to bring or stack an item will reward -1000}

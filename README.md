# David-Silver-DRL-
algorithms implementation for David Silver DRL courses

## policy iteration

###environment
* grid world
* Assumption: The agent can choose "hit the wall" action. If our agent choose "hit the wall" action, then the agent stays the same grid for the next state.
* label information, please refer to `Grid_World_Label_Definition.jpeg`

###results
* value function for each state
* possibility of the four actions for each state
* the same as the result shown by David

## policy iteration

###environment
* grid world 
* Assumption: The agent can choose "hit the wall" action. If our agent choose "hit the wall" action, then the agent stays the same grid for the next state.
###results
* value function for each state
* the same as the result shown by David

## Monte Carlo Control

###environment
* Blackjack
* Game Rule: 
	1. First step : the dealer and player have two cards, one of the dealers is called "showing card"
	2. Second step : the player can choose "stick"(stop getting card) or "twist"(get one more card) until the player's sum is over 21 or choose to stick.
	3. Third step: the dealer's policy is fixed: if the dealer's sum is over 17, twist, otherwise,stick. 
	4. The person whose sum is over 21 loses.
	5. If no one busts, the person whose sum is bigger wins.
	6. Assumption: 1-9 stands for 1-9, 10-13 stands for 10, the probalibility of getting any card is the same for every round (get card with replacement).
	
###results
* policy result (when to twist and when to result)
* average value function 

## Sarsa

###environment
* cliffwalking
* Game Rule: Get to the goal using as less steps as possible
	
###results
* `Sarsa_qlearning_comparison`
* `Sarsa_Qlearning_Track_Comparison.png`
* `cliff_walk_state_transition_different_parameter`
* 


## Q learning

###environment
* cliffwalking
* Game Rule: Get to the goal using as less steps as possible
	
###results
* `Sarsa_qlearning_comparison`
* `Sarsa_Qlearning_Track_Comparison.png`




### Brief:

In the assignment we had to use tick wise changes with simple rules to generate complex behaviour in the movement of grid tiles representing sand and water. We had to make a new grid and change the old grid with it every tick. 





**Question 1. Why does the swap grid start as a copy of the current state, rather than being**

**filled with zeros? What would happen to a grain that does not move if G′ started empty?**



Answer) If we don't have G be a copy of the current state, then the grid tiles that old change don't get copied over to G and therefore not to the next grid



**Question 2. Remove the randomised column order and replace it with a fixed left-to-right**

**scan. Run the simulation for a few hundred ticks. What happens to the shape of a sand pile?**

**Why?**



Answer) The sand pile develops a slope in one direction because left grid tiles always move before right grid tiles, it is a positive slope


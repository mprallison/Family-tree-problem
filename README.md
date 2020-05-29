# Family-tree-problem
Script to help find the logical limits of family trees

Arriving at this project was inspired by the House of Habsburg (look up their family tree) and a mental challenge Scott and I arrived at on holiday. We tried to work out whether it was possible for your brother to also be your uncle, or mother to also be your grandmother. We found these hard, and expanding the problems to three relationships was beyond our mental capacity. But this made for a nice programming challenge. 

The current relationships in scope are parents, grandparents, aunt/uncle, offspring, siblings, grandchildren, niece/nephew. 
I don't think adding more generations adds logical problems, and cousins become hard to define without a strict hierarchy of generations.
As the challenge is set out as purely logical, we assume that no one ever dies, infertility does not exist, no one goes to prison, and siblings need share only one parent. 

I imagine that there are mathematical approaches wherein axioms and formal proofs could actually define logical limits of what family relationships could be attributed to a single individual. It is de facto clear that a given individual cannot be your son and father, nor can your sister be your brother. But I'm not sure if all relationship combinations could be derived formally...

My solution settles on a brute force approach with no axioms. Family trees are iteratively generated and assessed until the relationships are satisfied or we run out of iterations. 

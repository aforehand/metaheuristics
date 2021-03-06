# metaheuristics

Genetic local search generates a population of randomly seeded MLPs
and trains them on given data. It then selects the models with the
lowest loss to serve as 'parents' for the next generation of models.
The 'child' models are generated by randomly choosing between the 
weights of pairs of parent models and mutating a small number of 
weights. This process of repeated until the specified number of 
generations is reached. The model with the lowest loss is returned.

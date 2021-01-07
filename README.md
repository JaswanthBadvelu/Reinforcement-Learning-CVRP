# Reinforcement-Learning-CVRP
In recent years machine learning is evolving at a phenomenal rate and can tackle tough problems on its own. The recent research work in the field of combinatorial optimization shows that machine learning has the potential to learn and design heuristics better than the traditional heuristics designed by humans. In this project, a reinforcement model with dynamic encoder-decoder architecture is developed that learns to design its heuristics based on the data to solve a large-scale
vehicle routing problem with optimality. The trained models produce the near-optimal solution instantly, without the need to retrain the models. When compared, with other heuristic approaches like the Savings Clarke wright algorithm which is implemented in Google’s Operation research tools this reinforcement model outperformed them. This proposed model can be easily extended to solve other variants of VRP problems like multi depot and VRP with Time windows.

The Dynamic Attention Model used here for solving VRP is inspired from the paper by Peng on the topic **A Deep Reinforcement Learning Algorithm Using Dynamic Attention Model for Vehicle Routing Problems** which can be found [here](https://arxiv.org/abs/2002.03282)

# Acknowledgements
Thanks to [Dmitry Eremeev](https://github.com/d-eremeev/), [Alexey Pustynnikov](https://github.com/alexeypustynnikov) for providing complete code implementation for this paper and making it public.Code implementation for this project can be found in the github repo [here](https://github.com/d-eremeev/ADM-VRP).

# pacman_mdp_and_reinforcement_learning_algorithms
Various algorithms for Markov's Decision Process and Reinforcement Learning in a grid world and in Pacman, including Value Iteration, 
Q Learning and Approximate Q-Learning.All code is provided by UC Berkeley, apart from the algorithms in question.

## Value Iteration
To play around with value iteration for Markov's Decision Process, you can use the following commands.
```
python gridworld.py -a value -i 100 -k 10
python gridworld.py -a value -i 5
```

## Q-Learning
To play around with Q-learning for Markov's Decision Process, you can use the following commands.
```
python gridworld.py -a q -k 5 -m
```

## Epsilon Greedy
To play around with Epsilon Greedy for Markov's Decision Process, you can use the following commands.
```
python gridworld.py -a q -k 100
python gridworld.py -a q -k 100 --noise 0.0 -e 0.1
python gridworld.py -a q -k 100 --noise 0.0 -e 0.9
```
To play around with a crawler learning to walk, you can use the following commands.
```
python crawler.py
```

## Q-Learning and Pacman
To play around with PacMan using Q-Learning, you can use the following commands.
```
python pacman.py -p PacmanQAgent -x 2000 -n 2010 -l smallGrid
python pacman.py -p PacmanQAgent -n 10 -l smallGrid -a numTraining=10
```

## Approximate Q-Learning
To play around with training pacman with Approximate Q-Learning, you can use the following commands.
```
python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -x 50 -n 60 -l mediumGrid
python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -x 50 -n 60 -l mediumClassic
```

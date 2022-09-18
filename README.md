# A Genetic Algorithm Based Flappy Bird Bot

## How to Run
- Make a new virtual environment and activate it (optional)
  - ` python3 -m venv env`
  - ` source env/bin/activate `
  - ` pip install --upgrade pip `
- Install Requirements
  - ` pip install -r requirements.txt`
- Run it! ` python3 flappybird.py `

## How it works

- Using the genetic algorithm, we train the individual instances of little birdies to navigate the maze of pillars on their own!

- The genetic algorithm mimics the process of Natural Selection. "Genes" (individual attributes (in our case, numbers) which contribute in a calculation used to take the decision (in our case, whether to jump at a particular condition or not)) make up "Chromosomes" which make up an instance in a "Population" (More Info)[https://towardsdatascience.com/introduction-to-genetic-algorithms-including-example-code-e396e98d8bf3]


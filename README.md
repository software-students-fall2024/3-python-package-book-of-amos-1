# Pymagotchi

![Workflow log](https://github.com/software-students-fall2024/3-python-package-book-of-amos-1/actions/workflows/event-logger.yml/badge.svg)

A Python-based virtual pet simulation package with customizable care and stats tracking.

## Features

- **Feed** your pet to keep it from getting hungry.
- **Play** with your pet to keep it happy.
- **Rest** your pet to give it energy.
- **Track** your pet's stats (hunger, happiness, energy, and health).
- **Time-based simulation**: Pet stats update over time, requiring regular care.

## Links
* PyPI page: https://pypi.org/project/pymagotchi
* GitHub repo: https://github.com/software-students-fall2024/3-python-package-book-of-amos-1

## Installation

Install pymagotchi via pip:

```bash
pip install pymagotchi
```

## Usage
Once installed, you can run pymagotchi from the terminal to start the game.
```bash
python -m pymagotchi
```
Alternatively, you can create and interact with your pymagotchi pet within your python code.
```python
from pymagotchi import Pet

# Create a new pet
my_pet = Pet.new_pet()

# Display the pet's stats
my_pet.status()

# Interact with the pet
my_pet.feed(amount=1)
my_pet.play(duration=5)
my_pet.sleep(duration=10)
my_pet.rename(new_name='new name')

# Display ascii representation of pet
my_pet.display()
```
## Pet Commands

* Feed
* Sleep
* Play
* Rename

## Requirements
Python 3.7 or higher.

## Contributing

## Authors
* https://github.com/bairixie
* https://github.com/dm6288
* https://github.com/naruminato1
* https://github.com/simesherbs


<p align="center">
  <a href="" rel="noopener">
 <img width=auto height=200px src="https://imgur.com/4Ocdxhz.jpg" alt="Project logo"></a>
</p>

<h3 align="center">ML2-MARL-ENV</h3>

<div align="center">

<!-- [![Status](https://img.shields.io/badge/status-active-success.svg)]() -->
<!-- [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE) -->

</div>

---

<p align="center"> Multi-agent Reinforcement learning environments
    <br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Dependencies](#Dependencies)
<!-- - [TODO](../TODO.md) -->
<!-- - [Contributing](../CONTRIBUTING.md) -->
<!-- - [Authors](#authors) -->
<!-- - [Acknowledgments](#acknowledgement) -->

## 🧐 About <a name = "about"></a>

Winter Intership program for `tmha@ML2`. [Tae Min Ha / github](https://www.github.com/taemin410)

## 🏁 Getting Started <a name = "getting_started"></a>


### Prerequisites

To install requirements for this repo : 

```
pip install -e .
```

---
## ⛏️ Usage <a name = "Usage"></a>

```
python main.py --mode=[modeargs]
```

- To train models using baselines 
- run trained model to visualize the result  

## ⛏️ Dependencies <a name = "Dependencies"></a>

- [Gym](https://gym.openai.com/) - gym environment for RL envs
- [baselines](https://github.com/openai/baselines/) - Reinforcement learning framework baselines
- [pygames](https://www.pygame.org/) - Pygames framework for games ran in python


## 🔧 Running the tests <a name = "tests"></a>


```
pytest
```


## 🎈 Fully-trained snake game via docker 
### Competition setting
- Each of the agents' goal is to maximize its own reward
- Snake reward is only given when it eats an apple(+1) and when it collides(-1). When a snake hits the wall or the body of the other snake it terminates the agent's game.


<!-- ## 🎈 Usage <a name="usage"></a>

Add notes about how to use the system.

## 🚀 Deployment <a name = "deployment"></a>

Add additional notes about how to deploy this on a live system.

## ⛏️ Built Using <a name = "built_using"></a>

- [MongoDB](https://www.mongodb.com/) - Database
- [Express](https://expressjs.com/) - Server Framework
- [VueJs](https://vuejs.org/) - Web Framework
- [NodeJs](https://nodejs.org/en/) - Server Environment

## ✍️ Authors <a name = "authors"></a>

- [@kylelobo](https://github.com/kylelobo) - Idea & Initial work

See also the list of [contributors](https://github.com/kylelobo/The-Documentation-Compendium/contributors) who participated in this project.

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Hat tip to anyone whose code was used
- Inspiration
- References -->

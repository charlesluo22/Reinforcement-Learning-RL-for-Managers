# Learning by Trial and Error: Reinforcement Learning for Managers

A companion extra to *Supply Chain AI in Python*, written for [scmaiteaching.org](https://scmaiteaching.org), for the book's Executive track: readers who run notebooks as-is and focus on what the results mean for a business. It is not part of the book.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23970433.svg)](https://doi.org/10.5281/zenodo.23970433) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/charlesluo22/Reinforcement-Learning-RL-for-Managers/blob/main/RL_for_Managers.ipynb)

Reinforcement learning (RL) is learning a sequence of decisions by trial and error, from a score that may come only at the end. This notebook explains it for managers, with a dog, a maze and a treat, and no coding:

1. **What is RL, anyway?** A dog with no map, wandering at random.
2. **Learning from experience:** what learning costs, and why it happens in a simulator.
3. **Explore or exploit:** settle for the snack, or look for the treat.
4. **What you reward is what you get:** the price of mud.
5. **Before you fund it:** a simple rule against two learners, one of which can see where the treat is.
6. **Back to the supply chain:** a manager's checklist, questions for the analytics team, and a one-page decision memo.

With the settings as shipped, each experiment checks its own results; once you change a setting, the checks are skipped.

## Running it

- **On Colab:** open the notebook with the button above, then choose *Runtime → Run all*. It needs nothing installed (Colab already has numpy and matplotlib); its first cell has step-by-step help for a first time in Colab. In a test run on a laptop (4 Nov 2026) the whole notebook took about 15 seconds; Colab may take longer.
- **On your own machine:** Python 3 with numpy and matplotlib, in Jupyter.

## License

The code cells of the notebook are under the MIT License (`LICENSE`). The license covers the code only, not the explanatory text.

## How to cite

Luo, C. C. (2026). *Learning by Trial and Error: Reinforcement Learning for Managers* (Version 1.0.0) [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.23970433

The details are in `CITATION.cff`.

## Contact

contact@scmaiteaching.org

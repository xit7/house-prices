# General information

This repository is working on the case of an hypothetical person Nicole Johnson is looking for a house and what recommendations I could give based on data.
The case is described in ["Case"](./assignment.md).

* [This is the final presentation PDF](./files/kingcounty-cmk.pdf) for technical reference
* [This is the final presentation Keynote](./files/kingcounty-cmk.key) for technical reference
* [This is the notebook](./assignment-analysis.ipynb) for technical reference
* [This the interactive map of affordable houses](./files/map_affordable.html)
* [This the interactive map of affordable + Neighbours](./files/map_crowded.html)
* [This the crowded heatmap](./files/map_crowded.html)

## Setup
### Requirements / Environment

This repo contains a requirements.txt file with a list of all the packages and dependencies you will need. Things to do:

```bash
brew update
```

In order to install the environment you can use the following commands:

```
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
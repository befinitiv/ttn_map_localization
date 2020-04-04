# Lora localization visualization in Jupyter

This repository contains Jupyter notebooks for visualizing TheThingsNetwork data, focusing on localization experiments.

## What this does

The code in here allows you to connect to the TheThingsNetwork and record and display receptions of Lora nodes. The receptions are visualized on a map as a circle around the gateway which received the packet.
In addition, the notebook also allows to load GPX tracks that can be used as a groundtruth for localization experiments.

## Running the notebook

Thanks to the MyBinder service, all you need to do is to just click onto the link: [MyBinder](https://mybinder.org/v2/gh/befinitiv/ttn_map_localization/master?filepath=ttn_map_localization.ipynb)

(Note that MyBinder does not allow connections to TTN network. Therefore, you can only load recordings of TTN and GPX data)

To run the notebook on you PC, you simply have to run

```
pip3 install jupyter-repo2docker
jupyter-repo2docker -E .
```

# Riak TS Demo

This demo shows how Riak TS can be used for analysis of time series data.
The goal is to predict the presence of a baseball game at Dodgers stadium using the traffic data
from the ramp sensor on the 101 North freeway in Los Angeles.

![More details about this dataset]("https://archive.ics.uci.edu/ml/datasets/Dodgers+Loop+Sensor")

## Installing
Prerequisites: Python 2.7.10, latest version of Riak TS.
Install python dependencies.

```
pip install -r requirements.txt
```

## Run demo

Once you have all python modules installed start the demo:
```
ipython notebook traffic-demo.ipynb
```

# Chaos Toolkit Documentation Support Code

Support code for the [documentation](https://chaostoolkit.org/reference/tutorial/#declare-an-experiment-to-observe-the-weakness).

You may want to clone this repository to play with the code used in the
tutorials.

```
cd tutorials/a-simple-walkthrough
pip3 install -U -r requirements.txt
pip3 install -U chaostoolkit
```

## Overview 
We are going to set an expired certificate and restart the services. We will then call our application and see how it responds.

1. Define a Steady-State Hypothesis
    - We assume the services are running
    - We assume we can call the sunset service to retrieve the sunset time for a given city
2. Declare an Experiment


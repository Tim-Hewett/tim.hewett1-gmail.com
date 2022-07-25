# tim.hewett1-gmail.com
Tim Hewett Sportsmedicine &amp; Sports SCIENCE Biomechanics Projects

This is Our Simple Cost Effectiveness Analysis Python Project.

The goal of this project is to develop a simple and straight-forward program for running a cost effectiveness analysis for comparisons of different orthopaedic and sports medicine treatment procedures. A secondary goal is to bypass compex Bayesian biostatistical analyses that most clinical practitioners cannot perform or may not fully understand.

In order to run this code you will need to first import these 3 libraries in this manner:

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

The important calculation to compare the Cost Effectiveness of Procedure A versus Procedure B is the following:

("The total outcome score of procedure A" == ("final Quality of Life or QoLY score for Procedure A" * "final Functional Rating or IKDC or Marx score for Procedure A" / "surgical time for procedure A (in Minutes)" * Tunnel widening for (in mm) for Procedure A" * "total return to work or play or RTS time in weeks for Procedure A"))
RTStA = ("total return to work or play or RTS time in weeks for Procedure A")
print("The total outcome score procedure B" == ("final Quality of Life or QoLY score for Procedure B" * "final Functional Rating or IKDC or Marx score for Procedure B" / "surgical time for procedure B (in Minutes)" * Tunnel widening for (in mm) for Procedure B" * "total return to work or play or RTS time in weeks for Procedure B"))
RTStB = ("total return to work or play or RTS time in weeks for Procedure B")


https://github.com/Tim-Hewett/tim.hewett1-gmail.com/blob/main/HewettLavenderSimpleCostEffectivenessAnalysisSCEA.ipynb

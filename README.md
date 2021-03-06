# Detect-Social-Distancing-for-COVID-19

A Social Distancing Analyser which automatically detects the extent to which social distancing protocols are followed in the area.

Get the areal time analytics such as:
   - Number of people in a particular area
   - Number of people in high risk
   - The extent of risk to a particular person.
  
# Input

![Input](https://user-images.githubusercontent.com/44723903/102654898-61b43800-4197-11eb-8280-868c8b970c42.gif)
  
# Requirements:
Python 3.8

Opencv(CV2) 4.2.0

numpy 1.14.5

argparse

# Working

Dark Red, Orange , Green points represents risk to human in Bird’s eye view. 

Dark Red: High Risk, Orange: Low Risk and Green: No Risk.

Red, Yellow lines between two humans in output tells they are violating social distancing rules.

# Output

![Output](https://user-images.githubusercontent.com/44723903/102655150-d12a2780-4197-11eb-91a0-7257f10de0c5.gif)

# ANSYS-Pressure-Difference Analysis

## Introduction and Problem Statement

ANSYS allows you to generate pressure simulation plots for a specific geometry but doesn't allow you to compare them. This code was written for Full Blue Racing Society at the University of Cambridge to allow the aerodynamics team to export the CSV files of these simulations and visualise the difference betweeen them. Although the problem may seem trivial at first, but the issue lies in the fact that the ANSYS CSV file does not contain data at the exact same datapoints, making it impossible to directly subtract the values. The matplotlib tri function was used to solve this.

## How to use the code
Input the path of the two csv files in a list as the primary argument of the function. An optional argument *divisions* can be added to specify how many parts the axes are divided into. If not specified, the argument is set as 1000, which provides a reasonable level of accuracy, and can be executed in a matter of seconds.

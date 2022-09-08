# python-scripts-internship
This repository contains a collection of Python scripts written during my internship in 2022 as a Javascript / Typescript Backend Developer. They were mainly written to complete auxiliary tasks in an efficient manner. Consequently, they were generally written very quickly and the quality of the scripts may be impaired accordingly. Nonetheless, notwithstanding time constraints, a best effort attempt has been made to make the code as readable, and reusable, as possible.

## prerequisites
1. In order to run this script locally, you will need files within the `data` folder of each script. 
2. You are strongly recommended to use a Jupyter notebook to view / run the scripts too.

## script summary
1. `csv_to_json_converter` - Convert CSV files into JSON files
2. `rent_estimate_visualisation` - Plot bar chart and histogram of an existing dataset

## csv_to_json_converter
This script converts csv files into JSON files of different formats / levels of hierarchy. Three separate, but highly similar, functions were written to convert the different csv files.

### future development
This script can be improved by
1. Making it more [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)
2. Making the function more generalised. Fields which are `keys` (non-leaf nodes) can be passed as one argument while fields which are `values` (leaf nodes) can be passed into another argument

## rent_estimate_visualisation
This script visualises an algorithm that predicts rent estimates. Visualisation is provided as a bar chart and a histogram.
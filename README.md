# An application of the cross entropy method to the TSP
An implementation of an approximation to the solution of Traveling Salesman Problem using cross entropy approach on Python 3. This project was created in order to replicate the results presented in the following paper 

[`De Boer, P-T., Kroese, D.P, Mannor, S. and Rubinstein, R.Y. (2005). A Tutorial on the Cross-Entropy Method. Annals of Operations Research, 134 (1), 19--67.`](https://scholar.google.ru/scholar?hl=en&q=A+Tutorial+on+the+Cross-Entropy+Method&as_sdt=1%2C5&as_sdtp=&oq=)

This repository contains an `.ipynb` in which you may find: 
  1. A function (`read_atsp`) that returns a `numpy` array that contains the costs of trips from `i` to `j` cities given URL to one of the datasets from [Zuse Institute Berlin](http://elib.zib.de/pub/mp-testdata/tsp/tsplib/atsp/index.html). (The code has not been tested on other datasets). 
  2. A `Python` `class` (`CrossEntropyTSP`) that helps to optimize the costs of a traveling salesman.
  3. An example of using both (with results).

# Positive Stress in Companies

This is a repository for code and data of the research project on Positive Stress in S&P 500 Companies.

* The research paper from this repository is available on [arxiv.org](https://arxiv.org/abs/2107.12362).

![Four Stress Types](/figures/quadrants.png?raw=true "Quadrants")

## Background

* We analysed over 400K company reviews to characterize companies in terms of four types of stress: negative stress, positive stress, passive, and low stress companies.
* Our analysis reveals the links between the four stress types through time and a major financial crisis, as well as the link between a company's stress type and its stock price.
  

## Structure

Code structure:

* `QuadrantAssociationFunction.ipynb` produces quadrant scoring in Figure 1.
* `analysis_temporal` produces temporal evolution of the four types of stress.
* `analysis_linguistic` produces BERTopics describing each stress type in companies.
* `analysis_stocks_growth` produces stock growth values across companies of the four stress types.
* `data_exploration` produces data statistics and data representatives analyses.

Data structure:

* `data` contains external variables on the US states, company headquarters, and unemployment rate through time.
* `preprocessed` contains master files produced by our initial analyses (e.g., review master with meta data and stress scores for each review and company master with company rating, stress, and quadrant scores).

Results structure:

* all the plots and linguistic analysis are stored in `results`.

## Running tests

Having installed the project's required packages using the `requirements.txt` file, you can run the repo's automated tests by using the command `pytest` at the root directory of the project. 

Make sure the `pytest` package is installed in your developer environment by running `pip install -U pytest` at the root directory of the project. Then, run the `pytest` command. 

A report will be generated indicating whether any of the tests are failing.

## Contact information
email: sanjascepanovic@gmail.com


### To report a bug:

Please use GitHub's issues function, or send me an email.

### For questions:

Please reach out by email.



## References

Šćepanović, S., Constantinides, M., Quercia, D., & Kim, S. (2021). Pressure Test: Good Stress for Company Success. arXiv preprint arXiv:2107.12362.

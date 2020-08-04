# Text-mining-of-employee-opinions

This project was done for the course Text and Network mining at HEC Montreal.
**The idea of the project was to analyze pros and cons of working in three different sectors represented by 14 companies:**

*	consulting - Big 4: EY, PwC, KPMG, Deloitte
*	telecommunication: Bell, Rogers, Telus, Videotron
*	banks:  Banque Nationale (National Bank), BMO, CIBC, RBC, Scotia Bank, TD

The data for this project - employees reviews of companies they work for - was collected on Glassdoor at the beginning of March 2020.
Whenever possible, 500 reviews per company, each containing pros and cons, were collected. In total, the dataset contains 6,431 reviews.

All the necessary text data pre-processing is done: puctuation removal, conversion to lowercase, stopword filtration, stemming and stem completion, creation of document-term and term-document matrices, etc.

This project is focused on descriptive analysis and includes the following:

* Correspondence analysis
* Factor analysis
* Analysis of chi-squared residuals
* Visualizations

Most of the analysis is carried out on single terms (uni-grams) and shows the high-level picture. A smaller part is devoted to bi-gram analysis (two-word combinations) which allows getting fine-grain information. 

Two identical code files are provided: in .Rmd and .R format.







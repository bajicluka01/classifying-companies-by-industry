#  Jernej Avsec's Data Science Project Competition journal

## February 2025 (1h)

* 28. (1h) Initial meeting at the company, familirazing ourselves with the problem and the requirements. 

## March 2025 (51h)

* 6. (8h) Preparation of all the enviromnents and research of the problem.
* 7. (10h) Scraping of all companies from naics website.
* 15. (10h) Scraping of all the codes from naics website and their top companies. 
* 28. (5h) Analysis of different LLM models. That includes their pricing, API structure, limits. (Gemini, ChatGPT).
* 29. (10h) Another scraping of data from Naics website. Now for complete descriptions and different informations for every NAICS code (Top companies, related codes, examples, description...)
* 30. (8h) Implementation of classification on Gemini model API.

## April 2025 (65h)

* 5. (15h) Implementation of framework using Luka's conceptual idea. This implementation includes robust loging functions, saving of models' outputs and calculation of necessary metrics.
* 6. (5h) Updates to Gemini model implementation so it works with framework.
* 10. (5h) Added additional metrics to framework (ratio of illegal codes, saving of illigal codes, multiple ground truths).
* 10. (3h) Implementation of Reevaluation model that enables re-evaluation of old outputs on new metrics.
* 14. (5h) Implementation of OpenAI model using their API, running some tests.
* 15. (8h) Updates to eval framework and test of Gemini and ChatGPT: Added ratio of illegal code per request (#ill_codes/#test_cases), Absolute accuracy (#matching_codes/#generated_codes), Removal of illegal codes before testing.
* 18. (8h) New version of Gemini and OpenAI models, analysis of illegal and mismatched codes in outputs of models.
* 23. (8h) Evaluated using new promts and conditions on probability.
* 25. (8h) Added gt from Gemini-naics6-v3_v2 mismatches and retested.
 
## May 2025 (100h)
* 3. (20h) Hierarchical model update, can now choose layers of generation and code metadata to use, testing, adaptation for OpenAI.
* 5. (5h) Conditional hierarchical.
* 12. (16h) Added production classification and parralel, first 10k.
* 15. (3h) Added tests, validations for new ground truths.
* 16. (8h) Prepared everything for classifier.
* 22. (8h) Added ModernBERT for soft probabilities
* 23. (8h) ModernBERT binary grond truth. 
* 24.-30. (32h) ModernBERT, logistic regression, neural network training, testing, validating. Analysis of results, writing of the report.
## Total: [217h]

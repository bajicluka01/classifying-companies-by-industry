# Luka Bajić's Data Science Project Competition journal

## February 2025 (1h)

* 28. (1h) Initial meeting at the company, familirazing ourselves with the problem and the requirements. 

## March 2025 (20h)

* 4. (5h) Scraped 6-digit NAICS codes from their website using BeautifulSoup library. Attempting to click on subpages using Selenium, without success - abandoning this approach. 
* 6. (1h) Setup AWS and BitBucket, studying sample_naics_classification data.
* 23. (10h) Created a script for random sampling from two datasets (PredictLeads' "ground truth" in FRI_data_naics_classification.jsonl and our scraped data from NAICS website in companies_all.json). Manually checked the correctness for cca. 200 companies (typically 1-2 codes each, sometimes up to 5) to obtain ground truth classification results.
* 24. (2h) Came up with a conceptual idea for a framework for the purpose of evaluating various models and determined the best way of storing the data and passing it between different parts of the code.
* 25. (2h) Identified outdated/invalid codes in FRI_data_naics_classification.jsonl, according to the 2022 list of NAICS codes.

## April 2025 (18h)
* 4. (2h) Implemented the necessary basics for the evaluation framework. 
* 7. (4h) Performed additional preprocessing, combined four different sources of ground truths, found even more invalid codes.
* 19. (7h) Analyzed invalid codes outputted by Gemini and GPT models with various contexts. Attempting to find patterns in these codes to minimize the total ratio of incorrect outputs. 
* 20. (5h) Performed analysis of Gemini model's outputs that do not agree with our current ground truths and determined that more than half of them are quite sensible. Additionally, found some errors/invalid codes in ground truths.

## Total: [39h]

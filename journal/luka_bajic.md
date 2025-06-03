# Luka Bajić's Data Science Project Competition journal

## February 2025 (1h)

* 28. (1h) Initial meeting at the company, familirazing ourselves with the problem and the requirements. 

## March 2025 (20h)

* 4. (5h) Scraped 6-digit NAICS codes from their website using BeautifulSoup library. Attempting to click on subpages using Selenium, without success - abandoning this approach. 
* 6. (1h) Setup AWS and BitBucket, studying sample_naics_classification data.
* 23. (10h) Created a script for random sampling from two datasets (PredictLeads' "ground truth" in FRI_data_naics_classification.jsonl and our scraped data from NAICS website in companies_all.json). Manually checked the correctness for cca. 200 companies (typically 1-2 codes each, sometimes up to 5) to obtain ground truth classification results.
* 24. (2h) Came up with a conceptual idea for a framework for the purpose of evaluating various models and determined the best way of storing the data and passing it between different parts of the code.
* 25. (2h) Identified outdated/invalid codes in FRI_data_naics_classification.jsonl, according to the 2022 list of NAICS codes.

## April 2025 (32h)
* 4. (2h) Implemented the necessary basics for the evaluation framework. 
* 7. (4h) Performed additional preprocessing, combined four different sources of ground truths, found even more invalid codes.
* 19. (7h) Analyzed invalid codes outputted by Gemini and GPT models with various contexts. Attempting to find patterns in these codes to minimize the total ratio of incorrect outputs. 
* 20. (5h) Performed analysis of Gemini model's outputs that do not agree with our current ground truths and determined that more than half of them are quite sensible. Additionally, found some errors/invalid codes in ground truths.
* 22. (8h) Implemented a code converter for old NAICS codes that the models sometimes output and integrated it with the evaluation framework. Generated ground truth #5 from Gemini's sensible outputs that were not in previous ground truths. 
* 23. (6h) Additional ground truth modification based on GPT's outputs. Comparison of the two models. 

## May 2025 (98h)
* 1. (5h) Wrote the first draft of the report.
* 5. (7h) Performed analysis of our current best model with the goal of increasing absolute accuracy. Modified ground truth with sensible outputs.
* 9. (5h) Preprocessed and analyzed newly received dataset with 100k companies.
* 10. (10h) Manually created ground truth annotations for 200 companies from the new 100k dataset.
* 13. (8h) Performed missing data analysis, to determine how much of the newly received data is useful for classification. Started working on fine-tuning DistilBERT for NAICS code classification.
* 15. (6h) Modified ground truth based on codes obtained by our best-performing model.
* 20. (7h) Switching from DistilBERT to ModernBERT. Additional data processing, multi-hot encoding, format change. 
* 24. (10h) New ground truth generation due to the new requirements for data exclusion based on string lengths. Manually classified 200 companies and checked Gemini's outputs and added them where necessary.
* 25. (6h) Wrote the second draft of the report.
* 26. (8h) Modified new ground truth by manually checking the obtained Gemini outputs. 
* 28. (9h) Manually checked the output of the newly trained classifiers (lightweight models). 
* 29. (8h) Compiled all relevant results from old logs. Prepared visualizations for the report. 
* 30. (9h) Finalized the report, improved the visualizations, added more detailed information about the data. 

## June 2025 (9h)
* 2. (5h) Presentation preparation.
* 3. (4h) Finishing touches and final presentation.

## Total: [160h]

# README #

## About this repository ##

The North American Industry Classification system is a standard for classifying companies. Unfortunately, the classification is readily available only for a small number of companies. We address this problem by developing an approach that can classify any company using a predetermined set of information about that company. Our approach is based on hierarchical prompting of a general-purpose LLM with company information and classification code descriptions. Using real-world data provided by PredictLeads, we demonstrate operationally acceptable performance for 6-digit codes and near-perfect performance for shorter codes. We also demonstrate how the approach can be scaled by training a secondary classifier. The scalable approach is currently below operationally acceptable performance, but is cost-effective and with a lot of potential for improvement.

Keywords: predictive machine learning, taxonomy/hierarchy classification, natural language processing

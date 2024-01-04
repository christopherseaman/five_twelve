# Data Dictionary

| hashed_column_name | definition | values |
| --- | --- | --- |
| account_id | the account identifier | unique ID |
| is_current_customer | whether the account is currently a customer | True/False |
| is_self_service | is the account a committed customers or do they have an online month-to-month subscription | True/False/NaN |
| is_arr_over_12k | is their rate of payment over $12,000 (annual) | True/False/NaN |
| company_revenue_bucket | what is the revenue of the account | Categories, most missing |
| country | the country the headquarters are located in | Most US/GB/NaN/IN/DE |
| state | the state the headquarters are located in | Abbrev, some missing |
| industry_grouped | their industry | Most Other/NaN/Tech/Mfg |
| has_crossbeam_data | if we have any crossbeam data on them | True/False |
| crossbeam_product1_customer | are they product1 customer in crossbeam | True/False/NaN |
| ... | ... | True/False/NaN |
| crossbeam_product23_customer | are they product23 customer in crossbeam | True/False/NaN |
| dnb_founded_time_grouped | the companies founded time | Before/after 2000, most missing |
| has_hg_data | were were able to get HG Insights data on this account | True/False |
| hg_product_27 | based on HG Insights, do they use product27 | True/False/NaN |
| ... | ... | True/False/NaN |
| hg_product_148 | based on HG Insights, do they use product148 | True/False/NaN |  
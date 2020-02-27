__Pipeline.ipynb__

- Contains main pipeline for this project, including data preprocessing stage and modeling stage

__FeatureEngineering - 1.ipynb__

- Previous_application.csv
  - Aggregate numerical columns to count, mean, max, min, sum
  - Aggregate categorical columns sum, mean --> counts, normalized_counts
- Opimization
  - Line_profiler for aggregation function
  - Multiporcessing for grouping by columns

__FeatureEngineering - 2.ipynb/ Bureau_data_2.ipynb__

- bureau.csv 
- bureau_balance.csv  

new features:
- aggregate numerical columns to count, mean, max, min, sum
- aggregate categorical columns sum, mean --> counts, normalized_counts
- bureau_balance.csv aggregate stats both by loan and by clients

computed new features:  
- late payment(installment_payments.csv)  
- credit utilization(credit_card_balance.csv)   
- debt ratio(bureau.csv)

__MPI_RF_final.ipynb__

- Contains source code for MPI implementation on hyper parameter tuning over Random Forest model
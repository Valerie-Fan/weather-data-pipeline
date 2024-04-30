# weather-data-pipeline
## Introduction
This repository aims to extract real-time data from Open Weather API, and upload it to AWS S3 bucket. This project will be using Airflow for data orchestration, EC2 for running intances, Python and Pandas for data preprocessing and Amazon Wed Serveces for dara storage, crawling, and visualization. 

## Architecture
![2024-04-30 9 05 49 (1)](https://github.com/Valerie-Fan/weather-data-pipeline/assets/164007751/00938e34-d683-4b9b-b1a8-9c70627783af)
## Final Result
Result demeonstrates the real-time temperature in Taipei using ASW Quicksight.
![截圖 2024-04-30 下午8 55 06](https://github.com/Valerie-Fan/weather-data-pipeline/assets/164007751/8205c652-0bf0-45db-838b-8693a63a0624)
## Prerequisites 
1. An AWS account.
2. Open Weather account and API.

## Workflow
1. Launch an EC2 instance, connect it to your local machine.
2. install dependencies on the environment.
3. Check if Airflow webserce works.
4. Fill in your amazon access key, secret key, and Open Weather API key in weather_dag.py.
5. Then run the dag on airflow and EC2 instance, you should see the data be stored in your S3 bucket.

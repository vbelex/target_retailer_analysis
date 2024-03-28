# Target Retailer Analysis
## Questions and Answers

**Author**: Vaibhav S. Borkar <br />
**Email**: vaibhavborkar@gmail.com <br />

:exclamation: If you find this repository helpful, please consider giving it a :star:. Thanks! :exclamation:


**1.**  List the total number of reported crimes between 2018 and 2023?

````sql
select column_name, data_type from `target_dataset.INFORMATION_SCHEMA.COLUMNS`
where table_name = 'customers'

````

**Results:**

|column_name |	data_type |
|------------|------------|
|customer_id | 	STRING |
|customer_unique_id |	STRING |
|customer_zip_code_prefix |	INT64 |
|customer_city |	STRING |
|customer_state |	STRING |


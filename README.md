# Data-Analyzing-using-SQL
here you can see some of my SQL projects

1. in the link bellow from BigQuery I have a data about some products of a company, I need to see the purchase prices, and sort them in Decs order, but there is a mistake happening that shows 89 on top of 799, by looking at the schema I see some of the numbers are saved as str type rather than num, so I use CAST to change the data all to float64, in the othe query in this link I used COALESCE() function to use product_code incase in the product column the name was null:
https://console.cloud.google.com/bigquery?sq=250354816806:1df5830758804ccda3b8c11bb4d99de1

2. in the link bellow from BigQuery I used the same data as above in number 1 link, and used CONCAT() function and SUBSTR function to have the product code along with the product color of the couch product and the price:
https://console.cloud.google.com/bigquery?sq=250354816806:9e120011bc6d434fafc3dae52e073346

3. in the link bellow I have a dataset abouth all the cars in market information, I see there is duplicates, so I removed the duplicates using ROW_NUMBER() function, some cars are filled up wrongly as 0 price I searched the internet and fille the cells using UPDATE and SET:
https://console.cloud.google.com/bigquery?sq=250354816806:2fcb268c146d40fb84d7166c732084b2

4. in the following link I have a data set about the county states in US, I used WHERE claus for filtering and ORDER BY claus for sorting he desired data:
https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=sdoh_cdc_wonder_natality&page=dataset&project=sorting-374409&ws=!1m9!1m4!1m3!1ssorting-374409!2sbquxjob_61592bd2_185a135a251!3sUS!1m3!3m2!1sbigquery-public-data!2ssdoh_cdc_wonder_natality

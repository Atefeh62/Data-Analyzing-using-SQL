# Data-Analyzing-using-SQL
here you can see all my SQL projects

1. in the link bellow from BigQuery I have a data about some products of a company, I need to see the purchase prices, and sort them in Decs order, but there is a mistake happening that shows 89 on top of 799, by looking at the schema I see some of the numbers are saved as str type rather than num, so I use CAST to change the data all to float64:
https://console.cloud.google.com/bigquery?sq=250354816806:1df5830758804ccda3b8c11bb4d99de1

2. in the link bellow from BigQuery I used the same data as above in number 1 link, and used CONCAT() function and SUBSTR function to have the product code along with the product color of the couch product and the price:
https://console.cloud.google.com/bigquery?sq=250354816806:9e120011bc6d434fafc3dae52e073346

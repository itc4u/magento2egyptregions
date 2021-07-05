# magento2egyptregions

As we know Magento don't provide list of Egypt regions we can add them by below method

Method to Add New Region for Specific Country in Magento 2:
Run the below SQL query:

INSERT INTO directory_country_region(country_id, code, default_name) VALUES ("country_code","region_code","region_name");

For example, I want to add a new region “Cairo” for India as shown below:

INSERT INTO directory_country_region(country_id, code, default_name) VALUES ("EG","CAI","القاهرة");

Please go to https://itc-4u.com/seO8z to see the tutorial

Regards,

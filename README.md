# home_sales

In this challenge, I used saprkSQL in Google Collab to run queries on home sales data to analyze and extract specific information from the dataset.

# Steps Involved: 
1. Necessary libraries and functions were imported into Google Collab.
2. The home_sales.csv file was read using sparkSQL.
3. A temporary table "home_sales" was created.
4. Queries were written to analyze the dataset.

   <img width="436" alt="image" src="https://github.com/bhartikaushal/home_sales/assets/124011061/beef36ca-8d13-4098-877e-58e7296ee0f4">

   <img width="397" alt="image" src="https://github.com/bhartikaushal/home_sales/assets/124011061/6ac8847b-ffb4-4569-9d07-9fa73c771bc9">

   <img width="389" alt="image" src="https://github.com/bhartikaushal/home_sales/assets/124011061/1be89bf1-56d3-44c7-9278-df3a82e2b324">

   5. The temporary table 'home_sales' was cached. Using the cached data, a query was run to filter out the view ratings with an average price greater than or equal to $350,000.
   6. The dataset was partitioned on the "date_built" field on the formatted parquet home sales data. A temporary table was created for parquet data. A query was run to filter out the view ratings with an average price greater than or equal to $350,000. The runtime was compared to the uncached data.
      
      <img width="293" alt="image" src="https://github.com/bhartikaushal/home_sales/assets/124011061/33c55420-7370-4494-9a5b-10ee47051ad5">

   7. The temporary table was then Uncached.
  <img width="247" alt="image" src="https://github.com/bhartikaushal/home_sales/assets/124011061/6c9b9f38-f11d-4169-890c-3a02890a716b">

  <img width="269" alt="image" src="https://github.com/bhartikaushal/home_sales/assets/124011061/17418851-b380-4663-a888-1681aaa34509">


      


 


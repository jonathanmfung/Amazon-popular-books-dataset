# Amazon-popular-books-dataset
A Github dataset of the most reviewed and best-selling books on Amazon.
This Amazon dataset contains 2269 [best-selling](https://www.amazon.com/b/?ie=UTF8&node=16857165011&ref_=sv_b_3) books. Each book title on this Amazon dataset has gained 10,000 reader reviews or more, making them stand out as the most popular books available. 

<h2>Key data points included in this free dataset:</h2>

* ASIN
* ISBN10
* Categories
* Reviews count
* Avg. rating
* Number of sellers
* URL
* Image
* Final price
* Title
* Description
* Availability


This is a sample subset which was forked from the "Amazon bestseller products (public data)"
dataset which totals <b>1,742,990 Amazon best-selling products</b>. The data was exlusively extracted from Amazon using the <b>Bright Data Amazon Scraper</b>, which 
integrates 
rotating residential proxies and the web unlocker infrastructure. 


The full dataset that was extracted during the 2d week of May was reduced into a smaller subset using smart filter queries available on the Bright Data datasets 
control panel.

<h2>Data point filter queries used for filtering this Amazon data subset:</h2>


*   	categories: "Books"
*   	reviews_count: {"$gte":10000}

Additional filter query values that can be used: <b>ASIN, brand, # of sellers, price after discount, timestamp, best-seller rank, and more.</b>

Available dataset file formats: <b>JSON, NDJSON, CSV, XLSX</b>.

Dataset delivery type options: <b>API download, Amazon S3, Google cloud, Microsoft Azure, SFTP</b>.

Buy the full Amazon dataset on <b>[Bright Data datasets page](https://brightdata.com/products/datasets/amazon)</b>. Purchasing a smaller subset after using smart 
filters may reduce the final price. This dataset is available with monthly / weekly / daily refreshes and takes only 1 day to deliver.


<h2>More Amazon datasets available from Bright Data:</h2>

*   1,000,000 "Amazon Sellers" 
*   70,000,000 "Amazon Products and Reviews" 

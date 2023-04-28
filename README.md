# Recommender-Systems-in-E-commerce
Project Problem Statement
With the exponential growth of e-commerce platforms and the increasing number of products
available for purchase, customers are finding it challenging to navigate through the vast range
of options to find the most suitable products for their needs. People are turning towards various
e-commerce platforms like Amazon, eBay, etc., to purchase products that are of their liking
these days. E-commerce platforms are facing the challenge of increasing competition and the
need to improve customer retention and loyalty. Providing personalized product
recommendations is one way to address these challenges, but traditional recommender
systems often fail to account for important contextual factors such as a customer's current
needs, budget, and availability. Therefore, the aim of this project is to develop an intelligent and
dynamic recommender system that can take into account contextual factors in addition to
historical data and preferences to provide highly relevant and personalized product
recommendations to customers, thereby enhancing their shopping experience and increasing
customer loyalty for e-commerce platforms.
Data Set
The Amazon product co-purchasing network dataset[1] consists of purchase data from
Amazon.com, which was collected over a period of several years. It includes metadata and
customer reviews for over 548,000 products, as well as product-to-product co-purchasing links
for approximately 2.4 million pairs of products.
The metadata for each product is provided in the ‘amazon-meta.txt.gz’ file, which includes a
range of product information such as ASIN, title, group (e.g., Book, DVD, Music), sales rank,
similar products, categories, and product reviews.
Data format:
Id: Product id (number 0, ..., 548551)
ASIN: Amazon Standard Identification Number
title: Name/title of the product
group: Product group (Book, DVD, Video or Music)
salesrank: Amazon Salesrank
similar: ASINs of co-purchased products (people who buy X also buy Y)
categories: Location in product category hierarchy to which the product belongs (separated by
|, category id in)
reviews: Product review information: time, user id, rating, total number of votes on the review,
total number of helpfulness votes (how many people found the review to be helpful)
Each product is represented as a block of information that starts with the Id field and ends with
an empty line. The ASIN field serves as the unique identifier for each product. Other fields such
as title, group, salesrank, and categories provide additional information about the product that
can be used to develop recommendation algorithms.
The dataset covers a wide range of product categories, including books, music, DVDs, and
electronics. The metadata and co-purchasing links can be used to construct a network of related
products, which can be used to develop recommendation algorithms.
The dataset has been used in many research studies related to recommender systems, social
network analysis, and graph theory. It provides an excellent opportunity to explore the dynamics
of customer purchase behaviors and develop new recommendation algorithms.


Due to the size limit on uploads to GitHub, we uploaded all our data to our official Google Drive Folder [here](https://drive.google.com/drive/folders/15GFSOxY5qBnk-ubOP2uOWbDob8Ab-Nc-?usp=share_link)
1 Available here: https://snap.stanford.edu/data/amazon-meta.html


# Customer Segmentation and Marketing Campaign Response Prediction

## Project Overview

This project aims to enhance the understanding of customer segments and predict their responses to marketing campaigns. By clustering customers based on their purchasing behaviors and demographics, and by predicting their responses to promotional offers, companies can tailor marketing strategies to different customer groups, thereby increasing engagement and reducing costs.

## Dataset

### Context

A response model can significantly boost the efficiency of marketing campaigns and overall customer management. The objective is to predict who will respond to an offer for a product or service and to segment customers based on their purchasing behavior and characteristics.

### Content

The dataset includes the following features:

- **AcceptedCmp1**: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise
- **AcceptedCmp2**: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise
- **AcceptedCmp3**: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise
- **AcceptedCmp4**: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise
- **AcceptedCmp5**: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise
- **Response (target)**: 1 if the customer accepted the offer in the last campaign, 0 otherwise
- **Complain**: 1 if the customer complained in the last 2 years
- **DtCustomer**: Date of customer’s enrolment with the company
- **Education**: Customer’s level of education
- **Marital**: Customer’s marital status
- **Kidhome**: Number of small children in the customer’s household
- **Teenhome**: Number of teenagers in the customer’s household
- **Income**: Customer’s yearly household income
- **MntFishProducts**: Amount spent on fish products in the last 2 years
- **MntMeatProducts**: Amount spent on meat products in the last 2 years
- **MntFruits**: Amount spent on fruits products in the last 2 years
- **MntSweetProducts**: Amount spent on sweet products in the last 2 years
- **MntWines**: Amount spent on wine products in the last 2 years
- **MntGoldProds**: Amount spent on gold products in the last 2 years
- **NumDealsPurchases**: Number of purchases made with a discount
- **NumCatalogPurchases**: Number of purchases made using catalogues
- **NumStorePurchases**: Number of purchases made directly in stores
- **NumWebPurchases**: Number of purchases made through the company’s website
- **NumWebVisitsMonth**: Number of visits to the company’s website in the last month
- **Recency**: Number of days since the last purchase

### Acknowledgements

The dataset is based on the work by O. Parr-Rud, described in *Business Analytics Using SAS Enterprise Guide and SAS Enterprise Miner*, SAS Institute, 2014.

### Inspiration

The main objective is to train a predictive model which allows the company to maximize the profit of the next marketing campaign and better understand customer segments.

### Usability

9.12

### License

Other (specified in description)

### Expected Update Frequency

Never

### Tags

Business, Classification

## Project Description

### Customer Segmentation Analysis

To better understand the customer base, we performed clustering using the KMeans algorithm. Customers were grouped into 5 distinct clusters based on their purchasing behaviors, demographics, and response patterns to marketing campaigns.

Below, you will find the characteristics of each cluster represented in bar plots.

#### Cluster 1

![Cluster 1 Characteristics](path/to/cluster1.png)

#### Cluster 2

![Cluster 2 Characteristics](path/to/cluster2.png)

#### Cluster 3

![Cluster 3 Characteristics](path/to/cluster3.png)

#### Cluster 4

![Cluster 4 Characteristics](path/to/cluster4.png)

#### Cluster 5

![Cluster 5 Characteristics](path/to/cluster5.png)

### Predictive Modeling

In addition to clustering, we developed a predictive model to forecast customer responses to marketing campaigns. This model helps in identifying potential responders, thereby enabling more targeted and cost-effective marketing strategies.

## Conclusion

The customer segmentation analysis provides valuable insights into different customer groups, helping to tailor marketing strategies more effectively. The predictive model further optimizes marketing efforts by identifying likely responders, maximizing campaign profitability.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

### Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/customer-segmentation-marketing-response.git

# FLO RFM Segmentation

![images](/images/projects.png)

# Business Problem

[FLO](https://www.flo.com.tr) is a large e-commerce site in Turkey.

 FLO wants to segment its customers and determine marketing strategies according to these segments.

To this end, customers' behaviors will be defined and groups will be formed according to the clusters in these behaviors.

---

# Dataset Info

**Total Features:** 12

**Total Row:** 19.945

| Feature | Definition |
| --- | --- |
| master_id | Unique Customer Number |
| order_channel | Which channel of the shopping platform is used (Android, IOS, Desktop, Mobile) |
| last_order_channel | The channel where the most recent purchase was made |
| first_order_date | Date of the customer's first purchase |
| last_order_channel | Customer's previous shopping history |
| last_order_date_offline | The date of the last purchase made by the customer on the offline platform |
| order_num_total_ever_online | Total number of purchases made by the customer on the online platform |
| order_num_total_ever_offline | Total number of purchases made by the customer on the offline platform |
| customer_value_total_ever_offline | Total fees paid for the customer's offline purchases |
| customer_value_total_ever_online | Total fees paid for the customer's online purchases |
| interested_in_categories_12 | List of categories the customer has shopped in the last 12 months |

---

# Requirements

```python
matplotlib==3.5.2
pandas==1.4.3
```

---

# Author 
Oğuz Erdoğan

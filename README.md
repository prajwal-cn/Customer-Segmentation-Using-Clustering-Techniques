# **Customer-Segmentation**

![image](https://user-images.githubusercontent.com/127007794/229349890-72547d92-acd7-4d9f-8663-469189a26c53.png)

Please note that plotly figure will not show when it is uploaded to GitHib due to static stuff. So you can rerun the code once you have it on your Local machine or check out the Link I include in the repo that display the notebook on web.
Click here to see the note on nbviewer.

## **Business Problem**

Customer Personality Analysis is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers.

Customer personality analysis helps a business to modify its product based on its target customers from different types of customer segments. For example, instead of spending money to market a new product to every customer in the company’s database, a company can analyze which customer segment is most likely to buy the product and then market the product only on that particular segment.

**link to dataset:** here

## **Methodology**
Jupyter environment (Jupyter Lab or Jupyter notebook) – for experimenting our project.
Pandas – For loading data as a dataframe and wrangling the data.
Numpy and Scipy for performing some basic mathematical computation.
Scikit-Learn – For building our Customer Segmentation Model.
Seaborn, Matplotlib and Plotly Express – for data visualization.
KneeLocator

## **Insights and Conclusion**

Firstly from the EDA we saw that Income was really the key indicator that was determined the amount a customer will spend. 

![image](https://user-images.githubusercontent.com/127007794/229349940-7f88c72c-6262-4b1a-bad5-c84ee117fe5d.png)

Also In terms of Education we noticed customers with graduate education level and above tends to spend 12 times higher than those customers with undergraduate education level. The reason for this is because customers with graduate education level and above earns above 2 times than customers with undergradute education level. 

![image](https://user-images.githubusercontent.com/127007794/229349948-d9f42cbe-2ad9-4f24-8ddd-3442d71c6a06.png)

Also we noticed a trends in terms of total children and total amount spent. We saw that on average there was a decline on the amount spent as the total number of children increases.I.e, as children increases so do the amount spent on average reduces.
Result From Clusters

![image](https://user-images.githubusercontent.com/127007794/229349958-822f918c-23f2-4c67-9f8b-669f85cc5f18.png)


Thank you for reading.

# StarbucksEDA-CustomerSegmentation

<img src="https://user-images.githubusercontent.com/90456255/212074628-68fe2e85-50b9-49d0-a36c-9d9cafaf4f3c.jpeg" width="1600px">

<p style="text-align: center;color:#00704A;font-size:25px;"><strong>Introduction</strong></p>

It is natural that in order for you to serve your customer better , you need to understand your customer first .

The following project aims to develop certain customer demographics and segmentation which will allow the the company executives to understand their customers better , response of the customers to their promotional campaigns and how to push better offers .

> The following project analyses the data of various offers implemented at Starbucks during the course of 1 month and some part of the customer base reacted to it .

<p style="text-align: center;color:#00704A;font-size:25px;"><strong>Data</strong></p>

The dataset is divided into 3 parts : 

- <em>portfolio.csv</em> - data about offers ( 10 instances )
- <em>profile.csv</em> - data about customers (17,000 instances)
- <em>transcript.csv</em> - customers response to offers and all the transactions made by the respective customers (306,646 instances)


<p style="text-align: center;color:#00704A;font-size:25px;"><strong>Methodology</strong></p>

1. <p style="color:#00704A">The first and foremost step is to understand the problem statement entirely and make important deductions based on the statement .</p>


	+ What are we trying to find out ? Engagement of different types of customers and effectivity of Starbucks offer Campaign.
  	+ What are the important factors affecting the following ?
 	 + In what areas to focus in order to achieve max output . 
 
 
2. <p style="color:#00704A">Importing the required libraries .</p>

<div style="display:flex">

<div>
3. Loading the data .

+ The data consists of 3 parts . We call each part seperatly and assign 3 seperate dataframes to each .
 	
+ For further analysis of these data and how they correlate with each other , we can merge them and then analyse them further however , I usually extend this part to EDA and not in Loading the Data because the data we have just received might not be perfect . It is not right to make dedcutions without clearing your assumptions on the data and without cleaning it .

</div>
<img src="../Desktop/st1.gif" width="250px" height="450px">

</div>

4. <p style="color:#00704A">Data Wrangling / Cleaning</p>

	+ This is always an important step . This step becomes ground for clearing any assumptions about the data through hypothesis testing .
	+ Further , cleaning and transforming the data further prerares it for EDA . 
 
   >  Do keep in mind that data transormation here doesn't refer to minmax scaling or normalization . Simply conversion of irregular attributes to derive more regular attributes ( for example : dict value from offer Data ) .
<div style="display:flex">

<div>

5. <p style="color:#00704A">Exploratory Data Anlaysis</p>

	+ The following step involves getting to know your data to your full extent . Here , I try and visualise the data in order to bring important deductions that may help me in developing my model more effeciently .
	+ The following part is taken care of and explained in the `ipynb file` .

6. <p style="color:#00704A">Customer Segmentation</p>

	+ The following step involves getting to know your data to your full extent . Here , I try and visualise the data in order to bring important deductions that may help me in developing my model more effeciently .
</div>

</div>
<p style="text-align: center;color:#00704A;font-size:25px;"><strong>Results</strong></p>

The enitre customer base was segmented into 5 important clusters :

+ <p style="color:#00704A">Loyal Customers</p>  These customers made the most no. of transactions . The type of offer that prevailed during the time didn't really affect their decisions. Nothing could stop them from getting a coffee .
+ <p style="color:#00704A">Most Valuable Customers</p>  These customers spent the most amount of money and also had a high amount of money spent per transaction . Their response to offers were successfull as most of these customers completed roughly 80% of the offers they viewed .
+ <p style="color:#00704A">High Potentials</p>  These customers were highly sensitive to the offers at avail . They spent a high amount of money and completed roughly most of the offers they viewed . Low no. of transcation , more money spent and high rate of offer completion all point to the success of offers that dominated this part of the customer base .
+ <p style="color:#00704A">Offer Viewers</p>  These customers viewed of offers but didn't avail for many . Perhaps they didn't find any offers to motivate their purchases or either they form a continuous spectrum into the low engagers part of the customer base .
+ <p style="color:#00704A">Low Engagers</p>  These customers didn't really engage in Starbucks franchise as a whole .

The following deductions were made from some of the following inferences :


![mVSov](https://user-images.githubusercontent.com/90456255/212075618-dfadd2ee-c20d-4259-9c70-cc7ac7444eb1.png)
![ocVSov](https://user-images.githubusercontent.com/90456255/212075638-1fd1f8db-1ca6-4a05-a213-bcaba3934a6e.png)
![tVSov](https://user-images.githubusercontent.com/90456255/212075656-436d7c3b-4257-4772-b4ba-f91f4f2ae6dc.png)


Here is a list of customer demographics based on their respective Segment :

![cD](https://user-images.githubusercontent.com/90456255/212075683-222ee983-77ec-4a4d-8bc9-0df8bf0c5cdd.png)
![gD](https://user-images.githubusercontent.com/90456255/212075695-34b9af90-ab8d-407f-89e5-3116966e5020.png)
![aD](https://user-images.githubusercontent.com/90456255/212075709-6007a563-7893-4be4-9608-8bfa98f9b57d.png)
![iD](https://user-images.githubusercontent.com/90456255/212075720-49efcd85-d40e-4a06-b858-fcad2de67e05.png)
![spec](https://user-images.githubusercontent.com/90456255/212075761-a31e6d00-89eb-47e8-833a-7d03532e4ef6.png)


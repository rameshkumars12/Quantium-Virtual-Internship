# Quantium-Virtual-Internship

# Task 1: Data preparation and customer analytics

## **Goal :**  The goal of our task is to find the types of customers who purchase Chips and their purchasing behaviour within the region.

### Step 1: Data cleaning:

  * Merged the Transaction dataset and Purchase Behaviour dataset. 
  
  * Data columns were given in an ID form, so the columns were replaced with a valid dates.
  
  * The Product Name columns were categorized with only the products that are chips.
  
  * Removed special characters from the product name column.

### Step 2: Checking for Outliers:
  
  * Boxplot is used to check if the ouliers present in the dataset by visualizing.
  
  * Total Sales and Loyalty Card Number are tend to have outliers.
  
  *  The outliers were removed by using the IQR method.

### Step 3: Visualizing the data's of:

  * Total number of sales over a period of a year.
  
  * Total Number of Sales in Each Stores.
  
  * Total Number of Chips Sold.
  
  * Total number of chips bhought by different LifeStage Customers.
  
  * Brands and its Product counts.
  
  * Brands and It's Total Sales.
  
  * LifeStage and Their Segmentation.

### Step 4: Insights:

  *   Products of chips are likely to be **Decreased** in sales in the months of **Febraury and November** and **Increase** in sales in Near Summer holidays and Christmas i.e          **March & December**

  *   Chips products are sold higher in the month of **July**

  *   Multiple Number of stores have less sales in chips

  *   **Smiths Cmkle Chips Original 380g** is the **most sold** chip product.

  *   **WW Original CornChips 200g**  is the **least sold** chip product.

  *   **Older Families and Older Singles/Couples** spend more on buying the chips products.

  *   **New Families** spend little on buying the chips products.

  *   **OLDER SINGLES/COUPLES** bought more in the **Smiths Crnkle ChipOrgnl Big Bag 380g** product, which they spend upto **$7446.0**.

  *   **RETIREES** bought more in the **Smiths Crnkle ChipOrgnl Big Bag 380g** product, which they spend up to  **$6891.0**.

  *   **OLDER FAMILIES** bought more in the **Smiths Crinkle Chips SaltVinegar 330g** product, which they spend upto **$6526.0**.

  *   **YOUNG FAMILIES** bought more in the **Smiths Crnkle ChipOrgnl Big Bag 380g** product, which they spend upto **$5593.0**.

  *   **YOUNG SINGLES/COUPLES** bought more in the **Smiths Crnkle ChipOrgnl Big Bag 380g** product, which they spend upto **$5192.0**.

  *  **MIDAGE SINGLES/COUPLES** bought more in the **Smiths Crnkle ChipOrgnl Big Bag 380g** product, which they spend upto **$3693.0**.

  *  **NEW FAMILIES** bought more in the **Smiths Crnkle ChipOrgnl Big Bag 380g** **$1009.0**.


  *   **Kettle brand** has the highest number of chips products sold followed by Tostitos,Doritos,Cobs.

  *   **WW brand** has the lowest chips products sold.


  **Top 5 LifeStage and their Customer Type that Spends more money in buying chips products.** 

  *  OLDER FAMILIES        **:**  Budget     **:**         **$51318.7**

  *  YOUNG SINGLES/COUPLES  **:**  Mainstream     **:**  **$47476.6**

  *  RETIREES               **:**  Mainstream       **:**    **$47323.9**

  *  YOUNG FAMILIES         **:**  Budget           **:**    **$42678.5**

  *  OLDER SINGLES/COUPLES  **:**  Budget            **:**   **$41821.8**


 **Least 5 Lifastage people and segments that spend money on buying chips**

*  YOUNG SINGLES/COUPLES   **:** Premium        **:**      **$13158.6**

*  MIDAGE SINGLES/COUPLES **:**  Budget         **:**      **$11199.9**

*  NEW FAMILIES         **:**    Budget           **:**     **$6612.8**

*  NEW FAMILIES         **:**    Mainstream       **:**     **$5198.9**

*  NEW FAMILIES          **:**   Premium            **:**   **$3538.1**


# Task 2: Experimentation and uplift testing


## Step 1: Problem Statement:

 *  A dataset of a retail store has been given, The dataset consits of various factores like Loyalty Card Number, Date, Store Number, Transaction ID, Product Number, Product Name, Product Quantity, Total Sales, Pack Size, Brand, LifeStage, Premium Customers.


  *   So the retail store has launched New Trial Stores with an new layout ==> **77,86,88**.

  *  The Task is to find is trial store has made many impact on the customers shopping and total number of sales. The trial store period starts from February **2018 to April 2019.**

  *  With the given data we need to get the total number of Customers visited in Trial Stores, Control Stores, Other Stores and Total number of Products sold in Trial, Contol, Other Stores 

  *  To find the control stores we need to get the **highest correlation** to the trial store, In such way we can get a trial store.


## Step 2: Finding Control Stores:
  
  * Adding a new month ID column in the data with the format yyyymm.
  
  * **Calculating For each store and month calculate:**

    * Total Sales

    * Number of Customers

    * Transactions Per Customer 

    * Chips Per Customer 
    
    * Average Price Per Unit


  * Created a Dataframe with OverAllMeasure values.
  
  * Removed incomplte observation data's of store numbers 11, 31, 44, 76, 85, 92, 117, 193, 206, 211, 218, 252.

  * Selecting Pre-Trail Period.
  * Defined a function to find the control store by finding maximum correlation value from the stores.
  
  * Defined a function to find the control store by finding the maximum Standard Magnitude value from the stores.
  
  * By getting the average of correlation and Standrd manitude we get the control stores.
  
  * Visualizing the control stores with trail stores.

# **Conlcution:**

The new trial layouts has a huge impact on the customers and sales section the Category chip manager can implement the new layout in the other stores. When compared to the customers visits the sales were some what less. So the manager can provide some discounts for certian products of chips which were performing low.



# Certificate of Completion:



  
  





![Certiicate of Quantium](https://user-images.githubusercontent.com/84787925/134323966-0f612a78-6fca-4c36-b500-e78632bc5d40.PNG)

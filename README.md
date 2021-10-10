# Maven_Market_Dashboard
Dashboard created using Power BI with Maven Market dataset

Maven Market Dashboard:
![image](https://user-images.githubusercontent.com/38867261/136688152-d45bc3de-3329-402e-961d-736e47eb7532.png)



Maven Market Has Following Dataset:
1) Customers
2) Products
3) Regions
4) Return Data
5) Stores
6) Transaction Data

**Cleaning and Preparing data:**
In this phase we created New Columns based on existing data such as Full Name, Start Month, Month Name, Weekend, Customer Age etc
Also Added Conditional Columns to calculate Weekends, to check customer weath interms of is_home_ownwe and income level etc
Using Folder structure to manager transactions data (which contains more files related to transactions)
![image](https://user-images.githubusercontent.com/38867261/136688173-70466686-0071-4dc6-be91-3a4c2c8795e4.png)


**Building Relationships:**
Created one-to-many relationship between Data(Fact) and Dimentions(Lookup) tables, Data going through only "Downstream"
![image](https://user-images.githubusercontent.com/38867261/136688243-f8e9d41f-85e6-4e32-bdc5-fee853469578.png)


**Visualizing Data:**
In Report Menu, Created required Measures such as Total transactions, Total returns, profit, revenue, return rate, % of returns etc
![image](https://user-images.githubusercontent.com/38867261/136688304-21fc7986-51bf-400a-88ea-2da3234226e8.png)
Topline performance page, illustrates top 30 products, KPI on Profit, Transactions, returns along with Map visualizations based on Store locations with total transactions

![image](https://user-images.githubusercontent.com/38867261/136688369-594a42e5-2f11-4ee6-920d-4b3618ffdda1.png)
Notes Page, By using "Bookmark" feature created bookmarks for specific sales information and when user clicks on "i"(information) button, Page navigates to specific visualization

![image](https://user-images.githubusercontent.com/38867261/136688437-f8eeb3c7-d157-4c46-b8c1-ea496640e93c.png)
After clicking "Portland hits 1,000 sales in December" bookmark

![image](https://user-images.githubusercontent.com/38867261/136688470-ddc4cf58-3c69-4d7c-8722-0bab4b24704f.png)
After clicking "San Diego Sales" bookmark

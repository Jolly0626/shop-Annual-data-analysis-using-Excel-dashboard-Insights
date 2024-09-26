# shop-Annual-data-analysis-using-Excel-dashboard-Insights
performing DATA Cleaning, preprocessing, manipulation, visualization using Excel/Pivot Tables 


From Given data of the shop 

#data cleaning:
1.Check for blanks in the data using Fliter function.
2.Replace uneven data to structural data Ex: * In given data Gender cloumn contain [Men,M,Women,W],replace M into Men & W into Women using #ctrl+F --- Replace
                                             * In Qty column [1,2,One,Two] replace One into 1 & Two into 2
#Data preprocessing:
1.check for relavent data required for performing given Kpi's. If n't Create required columns form data
Ex: Date Column is in format of DD-MM-YYYY ,Kpi's requirement is for MONTH ... So insert New Column named as Month by using Text function #text(G2,'MMM')
    Age Column contaion different ages in numbers so ...insert a new column name it as Age group >=30 Adult,>=50 as senior,rest off them as Teenager  #if(f2>=30 , "Adult",if(f2>=50 ,"senior","teenager"))

#data Analysis:
1.create a pivot table for orders vs Amount
2.pivot table for top 5 status
3.pivot table for companies with most orders
4.pivot table for Age group with Respect to Gender
5.pivot tables most orders with respect to Gender
6.pivot table for order status

7. use new sheet to insert all the kpi's data into dashboard
8. add Slicers #MONTH #COMPANY #Category

#connclusion :
 31-49 years old women spend more from uttarpradesh,Telagana,Maharasta,Andhra Pradesh,Tamil Nadu status .August had the highest sales.Product saled mostly through Amazon.  



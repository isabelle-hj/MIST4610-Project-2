# MIST4610-Project-2
# Team: 
**Team Name:**

macNcheese

**Team Members:**

1. Arushi Charu [@arushicharu](https://github.com/arushicharu)
2. Isabelle Jordan [@isabelle-hj](https://github.com/isabelle-hj)
3. Nidhi Ramani [@nid20](https://github.com/nid20)
4. Sarah Serghi [@sserghi](https://github.com/sserghi)

# Database Description:

The data set that we chose to analyze and formulate hypothetical questions based on is called Real Estate Sales 2001-2020 GL. This data set was last updated on August 12, 2023, and it was published on the DATA.GOV website by Metadata on November 12, 2023. This dataset is huge; it contains 997,214 rows of data entry. A brief skim of the data set, specifically focusing on the “Town” column reveals that this data set contains information for houses across Connecticut, a state in the United States of America. This data set contains quantitative variables such as the Assessed Value of the property and the Sale Amount of the property. The data set also contains categorical variables such as the Property Type and Residential Type. These categorical variables can be useful when looking into more specific hypotheticals; we have an example of this later in our project. 

In terms of data types, this data set consists of 5 different data types. Serial Number (the “primary key” for this data set) is an INT data type. List Year is a YEAR data type. Date Recorded is of data type DATE. The most common data type in this data set is VARCHAR. Town, Address, Property Type, Residential Type, Assessor Remarks, and Location are all of data type VARCHAR. Finally, Assessed Value and Sale Amount are type DECIMAL, and Sales Ratio is of data type FLOAT. 


# Question 1:

**Does the assessed value of a property in Connecticut have a positive relationship with the sale amount listed for the property? In other words, can one use the assessed value of the property to estimate the sale amount?**

Importance: 

When an individual is house hunting, they may have to rely on Assessed Values of the property instead of Sale Amounts for the property. This can often be the case, especially for properties that have never been publicly sold before or properties that were sold a long, long time ago. If someone can use the assessed value of a property to estimate how much they would need to pay to own the house, they would have a much easier time making housing decisions. On the other hand, if the assessed values for properties in Connecticut are not positively related to the sale amount for the properties recorded in the data set, then an individual may have a harder time budgeting for paying for a house. 

Analysis:

# Question 2:

**What is the most expensive town to live in in Connecticut, and within that town, how do the different Residential Types rank in terms of Sale Amount?**

Importance: 

Importance: Depending on an individual’s spending budget, preferences for living standards (such as the quality of elementary schools in the area), and vision of lifestyle, and other personal preferences, he or she may want to live in the most expensive town in their state. 
On the other hand, many individuals may be hesitant to settle down in a town where the property value is much higher than surrounding towns. They might take factors such as high property taxes and cost of living into account when deciding where to settle down. In this case, an individual would avoid living in the town with the highest average Sale Amount value. 

After figuring out which city has the highest average Sale Amount, an individual may want to compare the average Sale Amounts for each type of Residential Type, also based on preferences, income, and other factors that the individual wants to consider. For example, a family that earns a lower amount of income may want to reside in a less expensive multi-family home (Two - Four Family Home) in order to have their needs met for their jobs, their schooling, or other residents in the home. Contrarily, a family that is better well-off in terms of income and has the resources to provide for their family without a problem may opt for a more expensive Single Family home since they have the ability to do so. 

Analysis: 

<img width="626" alt="Screenshot 2023-12-04 at 1 16 24 PM" src="https://github.com/isabelle-hj/MIST4610-Project-2/assets/148258434/5a32f7df-f61c-4fca-8297-ec68ebc3dcb8">


<img width="384" alt="Screenshot 2023-12-04 at 1 17 12 PM" src="https://github.com/isabelle-hj/MIST4610-Project-2/assets/148258434/f222af04-bfaf-4f0e-8ae7-fc650577f37e">


# Manipulations:

# Tableau Workbook:

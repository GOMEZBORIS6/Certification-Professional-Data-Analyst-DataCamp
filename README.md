# Certification-Professional-Data-Analyst-DataCamp
Certification and Project Overview for DataCamp's Data Analyst Professional Certificate Program
![data_analyst_linkedin](https://github.com/GOMEZBORIS6/Certification-Professional-Data-Analyst-DataCamp/assets/84849041/d4d252c9-9f99-4f3e-af1b-7d913bcb02ff)

# Practical Exam - Product Sales

## About Pens and Printers
Pens and Printers was founded in 1984 and provides high quality office products to large organizations. We are a trusted provider of everything from pens and notebooks to desk chairs and monitors. We don’t produce our own products but sell those made by other
companies. We have built long lasting relationships with our customers and they trust us to provide them with the best products for them. As the way in which consumers buy products is changing, our sales tactics have to change too. Launching a new product line is expensive and we need to make sure we are using the best techniques to sell the new product effectively. The best approach may vary for each new product so we need to learn quickly what works and what doesn’t.

***

## New Product Sales Methods

Six weeks ago we launched a new line of office stationery. Despite the world becoming increasingly digital, there is still demand for notebooks, pens and sticky notes. Our focus has been on selling products to enable our customers to be more creative, focused
on tools for brainstorming. We have tested three different sales strategies for this, targeted email and phone calls, as well as combining the two.
**Email:** Customers in this group received an email when the product line was launched, and a further email three weeks later. This required very little work for the team.
**Call:** Customers in this group were called by a member of the sales team. On average members of the team were on the phone for around thirty minutes per customer.
**Email and call:** Customers in this group were first sent the product information email, then called a week later by the sales team to talk about their needs and how this new product may support their work. The email required little work from the team, the call was around ten minutes per customer.

## Data Information

The sales rep has pulled some data from their sales tracking system for us. They haven’t included numbers for how much time was spent on each customer, but there may be some other useful customer information in [here](https://github.com/GOMEZBORIS6/Certification-Professional-Data-Analyst-DataCamp/files/15282394/product_sales.csv).
The data only relates to the new products sold. As there are multiple different products, the revenue will vary depending on which products were sold. You can find the data here. I will let you decide how to process it, just make sure you include all your decisions in your report. The data hasn’t been validated, so make sure that you check it against all of the information in the table before you start your analysis.

### *Dataset Description*

<table>
    <tr>
        <th><center> Column Name </center></th>
        <th><center> Details </center></th>
    </tr>
    <tr>
        <td><center> week </center></td>
        <td><center> Week sale was made, counted as weeks since product launch </center></td>
    </tr>
    <tr>
        <td><center> sales_method </center></td>
        <td><center> Character, which of the three sales methods were used for that customer </center></td>
    </tr>
    <tr>
        <td><center> customer_id </center></td>
        <td><center> Character, unique identifier for the customer </center></td>
    </tr>
    <tr>
        <td><center> nb_sold </center></td>
        <td><center> Numeric, number of new products sold  </center></td>
    </tr>
    <tr>
        <td><center> revenue </center></td>
        <td><center> Numeric, revenue from the sales, rounded to 2 decimal places.  </center></td>
    </tr>
    <tr>
        <td><center> years_as_customer </center></td>
        <td><center> Numeric, number of years customer has been buying from us (company founded in 1984)  </center></td>
    </tr>
    <tr>
        <td><center> nb_site_visits </center></td>
        <td><center> Numeric, number of times the customer has visited our website in the last 6 months  </center></td>
    </tr>
    <tr>
        <td><center> state </center></td>
        <td><center> Character, location of the customer i.e. where orders are shipped  </center></td>
    </tr>
</table>


## Written Report

Your written report should include written text summaries and graphics of the following:
- **Data validation**:
    - Describe validation and cleaning steps for every column in the data
- **Exploratory Analysis** to answer the customer questions ensuring you include:
    - Two different types of graphic showing single variables only
    - At least one graphic showing two or more variables
    - Description of your findings
- Definition of a **metric for the business to monitor**
    - How should the business monitor what they want to achieve?
    - Estimate the initial value(s) for the metric based on the current data?
- **Final summary including recommendations** that the business should undertake

Questions to need answers in this Exam: 
We need to know:

- How many customers were there for each approach?
- What does the spread of the revenue look like overall? And for each method?
- Was there any difference in revenue over time for each of the methods?
- Based on the data, which method would you recommend we continue to use? Some
of these methods take more time from the team so they may not be the best for us
to use if the results are similar.

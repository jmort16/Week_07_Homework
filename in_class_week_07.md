# Week 7 In-Class Group Assignment

1.  Create an account on lucidchart.com and create an ERD diagram for the following scenario:

 
![Week 7 ERD Diagram.png](https://github.com/jmort16/InClass/blob/f01ad9d276671df2b2cb0bfb908fd47457126cd5/Week%207%20ERD%20Diagram.png)


2.  With your group, create a list of at least 5 and no more than 10 ways data can be "dirty."

    a.  A column has one or more missing values -- To resolve it, I would fill each empty location with a standard default value that is appropriate for the type of data in that column.  (.fillna?)
    b.  Superfluous characters in a value within a column (such as a leading space or two spaces where there should only be one) -- To resolve it, I would iterate through the list and replace the extra spaces with ''.
    c.  Inconsistent formatting (such as 'Frank' v. 'frank') -- To resolve it, I would replace any faulty formats with the preferred one so that all entries are consistent.
    d.  Different data types within a column -- To resolve it, I would change the type of the values that were of the less popular type in the list, or if needed, I would replace the data entry with a comparable piece of information in the popular data type.
    e.  Duplicate entries throughout an entire row -- To resolve it, I would drop any rows that appeared to have no variety of information (since they add no value to the data set).
    
3.  I was immediately drawn to the FBI Crime Data API.  I thought it would be intriguing to compare crime data with unemployment data by locations and over time, so I found the US Bureau of Labor Statistics API (Civilian Unemployment Rates).  I'm assuming that data from this institution has been cleaned and examined for use, and there are plenty of questions to investigate in terms of how these APIs may relate to one another.
        APIs --  https://crime-data-explorer.fr.cloud.gov/pages/docApi and https://www.bls.gov/developers/api_signature_v2.htm
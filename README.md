## Learning SQL Through Doing


### Instructions

1. Ensure you have the [Chinook Database](http://chinookdatabase.codeplex.com/) and [SQLite Manager Firefox add-on](https://addons.mozilla.org/en-US/firefox/addon/sqlite-manager/) installed.
2. Fork this repo.
3. Clone the fork you created.
4. Each answer should be in it's own file. For example, the file contains your answer for question #1 would be `1.sql` and for question #17 the file name would be `17.sql`.
4. Push up your work, frequently.

For each of the following exercises, provide the appropriate query. Yes, even the ones that are expressed in the form of questions. Everything from class and the [Sqlite Documentation](http://www.sqlite.org/) is fair game. No Sharing of Answers. 

1. Provide a query showing Customers (just their full names, customer ID and country) who are not in the US.
2. Provide a query only showing the Customers from Brazil.
3. Provide a query showing the Invoices of customers who are from Brazil. The resultant table should show the customer's full name, Invoice ID, Date of the invoice and billing country.
4. Provide a query showing only the Employees who are Sales Agents.
5. Provide a query showing a unique list of billing countries from the Invoice table.
6. Provide a query showing the invoices of customers who are from Brazil.
7. Provide a query that shows the invoices associated with each sales agent. The resultant table should include the Sales Agent's full name. 
8. Provide a query that shows the Invoice Total, Customer name, Country and Sale Agent name for all invoices and customers. 
9. How many Invoices were there in 2009 and 2011? What are the respective total sales for each of those years?
10. Looking at the InvoiceLine table, provide a query that COUNTs the number of line items for Invoice ID 37.
11. Looking at the InvoiceLine table, provide a query that COUNTs the number of line items for each Invoice. HINT: [GROUP BY](http://www.sqlite.org/lang_select.html#resultset)
12. Provide a query that includes the track name with each invoice line item.
13. Provide a query that includes the purchased track name AND artist name with each invoice line item.
14. Provide a query that shows the # of invoices per country. HINT: [GROUP BY](http://www.sqlite.org/lang_select.html#resultset)
15. Provide a query that shows the total number of tracks in each playlist. The Playlist name should be include on the resulant table.
16. Provide a query that shows all the Tracks, but displays no IDs. The resultant table should include the Album name, Media type and Genre.
17. Provide a query that shows all Invoices but includes the # of invoice line items.
18. Provide a query that shows total sales made by each sales agent.
19. Which sales agent made the most in sales in 2009? HINT: [MAX](https://www.sqlite.org/lang_aggfunc.html#maxggunc)
20. Which sales agent made the most in sales in 2010?
21. Which sales agent made the most in sales over all?
22. Provide a query that shows the # of customers assigned to each sales agent.
23. Provide a query that shows the total sales per country. Which country's customers spent the most?
24. Provide a query that shows the most purchased track of 2013.
25. Provide a query that shows the top 5 most purchased tracks over all.
26. Provide a query that shows the top 3 best selling artists.
27. Provide a query that shows the most purchased Media Type.

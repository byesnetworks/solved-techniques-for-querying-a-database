Download Link: https://assignmentchef.com/product/solved-techniques-for-querying-a-database
<br>
Name the queries using numbers, in order, like Query 1, Query 2, Query 3 …<strong>For the queries we’ll use the following techniques:</strong> Wild card query. Or query. And query. Parameter query. Numeric range query. Combination of And, Or and conditions. Multiple tables query with some condition using inner joins. Statistics query using group by and some computation. Calculated field query.To create a query on Access Database:Create; Query Design; Select the table/s to query (Close pop up window when done); Drag down or double click relevant fields on the corresponding table views; Write selection criteria.As you try to close the Query by clicking the X on the upper right corner, Access will ask you to save it.To see your queries, make sure Tables and Related Views is checked on the left panel.<strong>Queries</strong>1. From the Owner table: display the first and last names of all owners whose first names contain the string jo. The jo string could be positioned anywhere on the first name. Hint: Use wild card *.2. From the Client table: display the Names and the State of all clients from New York or Florida. Hint: Use the Or logical operator or use two different rows on the query design, one condition per row.3. From all three tables: display owner’s Last and First Name, Client Name, Current Due and Unit Number of all units that are rented by a client from Iowa or New York who owes more than 500$. Hint: Use Or and put both criteria (in bold) on the same row (for implicit And). Note that query is not asking that the state be part of the answer.4. From the Client table: display the Names and the State of all clients from a state that the user enters.Hint: On the Criteria type [Enter State]5. From the Condo Unit table: display Weekly Rate, number of Bathrooms and Unit Number of all units with rates greater than or equal to $725 and less than $1000. Hint: Use comparison operators and logical And.6. From the Condo Unit table: display Unit Number, Bedrooms, Rented and Next Available of all two bedroom units which are rented (Yes) and also display Unit Number, Bedrooms, Rented and Next Available of three bedroom units available after January 1st 2017. Hint: This is a combination of And and Or query. One set of criteria on first row and the other set of criteria on second row.7. From all three tables: display owner’s Last and First Name, Client Name and Current Due of all units that have current due greater than $300 and are rented. Hint: This is an And query, two conditions on the same row. Note that rented is not supposed to be displayed on the answer table.8. From the Condo Unit table: display average weekly rates grouped by number of bedrooms.Hint: from Design on the ribbon click Totals to display the Total option on the query.9. From the Condo Unit table: display Unit Number, Current Due and Amount Paid.The insert a calculated field, which is not part of the database.

Right-click the Field row in the next open column in the design grid to display a shortcut menu.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/497.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/497.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Click Zoom on the shortcut menu to display the Zoom dialog box. Type Total Amount: [Amount Paid] + [Current Due] and click OK.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/953.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/953.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Your results should match the following tables. Please keep in mind that getting the same result does not necessarily mean that your query is right! Results could match by chance.1.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/504.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/504.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>2.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/365.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/365.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>3.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/549.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/549.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>4.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/766.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/766.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/914.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/914.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>5.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/829.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/829.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>6.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/806.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/806.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>7.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/665.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/665.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>8.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/891.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/891.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>9.

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/917.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2017/05/917.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>
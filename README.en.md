# Welcome to the All For One project repository

### README Translations:

-   [English](/README.en.md)
-   [Portuguese](/README.md)

* * *

## 👨‍💻 What was developed:

-   Project made to practice SQL concepts. The database used in this project was the`Northwind`. We have, in this project, a series of challenges with different levels of complexity that must be solved each one in its own file.

* * *

# project requirements

Build queries to find the information expected by the challenges:

## Initial Challenges

1 - Display only the product names in the table`products`.

* * *

2 - Display the data of all columns of the table`products`.

* * *

3 - Write a query that displays the values ​​of the column that represents the_primary key_from the table`products`.

* * *

4 - Count how many records there are in the column`product_name`from the table`products`.

* * *

5 - Build a query that displays the table data`products`from the fourth record to the thirteenth.

<details>
  <summary>&nbsp;&nbsp;<strong>👀 Observações técnicas</strong></summary>

-   Both the fourth and thirteenth records must appear in the query;

-   Do not use`where`or`order by`.

      <br />
    </details>

    * * *

6 - Display the column data`product_name`e`id`from the table`products`so that the results are in alphabetical order of names.

* * *

7 - Show only the ids of the last 5 records in the table`products`(sorting must be based on column`id`).

* * *

8 - Make a query that returns three columns, respectively, with the names 'A', 'Trybe' and 'eh', and with values ​​referring to the sum of '5 + 6', the string 'de', the sum of ' 2 + 8'.

<details>
  <summary>&nbsp;&nbsp;<strong>👀 Observações técnicas</strong></summary>

-   In the first column, display the sum of`5 + 6`(this sum must be performed by SQL);

-   In the second column there should be the word \\"from\\";

-   And finally, in the third column, display the sum of`2 + 8`(this sum must be performed by SQL);

-   The first column should be named \\"A\\", the second column should be named \\"Trybe\\" and the third column should be named \\"eh\\";

-   Do not use pre-existing columns, just what is created on the fly.

      <br />
    </details>

## Data filtering challenges

9 - Show all the values ​​of`notes`from the table`purchase_orders`which are not null.

* * *

10 - Show all data in the table`purchase_orders`in descending order, sorted by`created_by`wherein`created_by`is greater than or equal to 3.

-   Also sort the results by`id`increasingly, as a tie-breaking criterion for ranking.

    * * *

11 - Display the column data`notes`from the table`purchase_orders`in which its value of`Purchase generated based on Order`is greater than or equal to 30 and less than or equal to 39.

-   ✨ Tip:`Purchase generated based on Order`is a value assigned to the column`notes`and not a column.

    * * *

12 - Show the`submitted_date`of`purchase_orders`what to`submitted_date`is dated April 26, 2006.

* * *

13 - Show the`supplier_id`the`purchase_orders`wherein`supplier_id`be 1 or 3.

* * *

14 - Show the column results`supplier_id`from the table`purchase_orders`wherein`supplier_id`is greater than or equal to 1 and less than or equal to 3.

* * *

15 - Show only the hours (without the minutes and seconds) of the column`submitted_date`of all records in the table`purchase_orders`.

-   In the result, the hour extracted from the column`submitted_date`should be called`submitted_hour`.

    * * *

16 - Exhibit to`submitted_date`the`purchase_orders`that are between`2006-01-26 00:00:00`e`2006-03-31 23:59:59`.

* * *

17 - Show column records`id`e`supplier_id`the`purchase_orders`in which the`supplier_id`either 1, or 3, or 5, or 7.

* * *

18 - Show all records of`purchase_orders`who has the`supplier_id`equal to 3 and`status_id`equal to 2.

* * *

19 - Show the number of orders that were placed in the table`orders`fur`employee_id`equal to 5 or 6, and that were sent through the method(column)`shipper_id`equal to 2.

-   In the result, the column containing the order count should be called`orders_count`.

    * * *

## Table manipulation challenges

20 - Add to table`order_details`a record with`order_id`: 69,`product_id`: 80,`quantity`: 15.0000,`unit_price`: 15.0000,`discount`: 0,`status_id`: 2,`date_allocated`: NULL,`purchase_order_id`: NULL e`inventory_id`: 129.

-   ✨ Tip: The`id`should be incremented automatically. To better understand this, you can refer to the table creation file (./northwind.sql, on line 439)[here](https://github.com/betrybe/sd-023-b-mysql-all-for-one/blob/master/northwind.sql#L439).

    * * *

21 - Add with a single`INSERT`, two rows to the table`order_details`with the same data as requirement 20.

<details>
  <summary>&nbsp;&nbsp;<strong>👀 Observações técnicas</strong></summary>
  
  - Esses dados são novamente `order_id`: 69, `product_id`: 80, `quantity`: 15.0000, `unit_price`: 15.0000, `discount`: 0, `status_id`: 2, `date_allocated`: NULL, `purchase_order_id`: NULL e `inventory_id`: 129;

-   O`ìd`should be incremented automatically.

      <br />
    </details>

    * * *

22 - Update the data of`discount`do`order_details`to 15.

⚠️ To test locally, you may need to use the SAFE UPDATE, however**no need to add SAFE UPDATE statement in file`desafio22.sql`next to query**, as the evaluator itself will adjust this.

* * *

23 - Update column data`discount`from the table`order_details`to 30, where the value in the column`unit_price`is less than 10,0000.

-   ✨ Tip: It is not necessary to use SAFE UPDATE in your query.

    * * *

24 - Update column data`discount`from the table`order_details`to 45, where the value in the column`unit_price`is greater than 100000 and the id is a number between 30 and 40.

-   ✨ Tip: It is not necessary to use SAFE UPDATE in your query.

    * * *

25 - Delete all data in which the`unit_price`from the table`order_details`is less than 10,0000.

* * *

26 - Delete all data in which the`unit_price`from the table`order_details`is greater than 10,0000.

* * *

27 - Delete all data from the table`order_details`.

* * *

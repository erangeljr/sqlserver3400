Give a relational database schema with the following relations:

	Hotel( hno, hname, city )
	Room ( hNo, rNo, type, price)
	Guest( gNo, gName, address)
	Book ( gNo, hNo, rNo, sDate, eDate)

Answer the following queries in relational algebra, relational caculus:

1. List all hotels which have at least one room with price > $1000.

2. List all hotels which have at least 2 rooms with price > 1000.

3. List hotel chain names which have at least 2 rooms with price > 1000.

4. List city names that have a least 2 hotel chains in the city.

5. List guests who have reserved a room > $1000 (rich guys).
5-2. List guests who reserved only rooms with price > 1000 (Super rich.

6. List hotels that have no customers who have more than 1 reservation
(hotels with very poor service)

7. List customers who have booked rooms in the same hotel during John Doe
stay in Holiday Inn between 2/1/87 - 2/5/87 (find out the killers)

8. List all customers who lived at least one day in NY hotels  between
9/8/01 and 9/11/01.

9. List customers who have never booked a room in the same hotel that John
Doe has.

10. List hotels that has cheapest rooms.

11. List hotels that have the second least expensive room.

12. List customers who have booked in each of all hotels.

13. List guest who have reservation on each of hotels in the
    city of Las Vegas.

14. List hotel chains that have hotels in each of all cities in the
    database. 

15. List hotels that have exactly one room with price > $1,000.

16. List hotel chains that have  exactly one room with price > $1,000.

Can the following queries being answered by relational algebra or
relational calculus?

1. List each of all city names and the number of hotels in the
   city.

2. List each of all hotels and its total sales of 2002.

3. For each hotel, list its
	- number of rooms,
	- the most expensive room price,
	- the least expensive room price,
	- the average room price.
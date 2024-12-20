# Database_A3



CASE STUDY
UEFA Champions League (UCL) is one of the biggest football competitions
conducted by the Union of European Football Association. Started in 1955, UCL is
one of the most viewed and anticipated football tournaments in the world. You
are provided with an excel sheet containing data for UCL 2016-2022.


PART#1 – Design (50 Marks)

1. Design SQL Schema for the given dataset. Identify the Entities/Tables and
corresponding columns, constraints, and primary keys. Also, identify the
relationships between different Entities and map them through foreign keys
correctly.
2. Identify the functional dependencies in each table and classify them as a full
functional or partial functional dependency.
3. Identify the current normal form of each table using conditions studied in class
and apply normalization to remove bad relations (if required). If you think,
normalization is not required, justify it.




PART#2 – Insertion (20 Marks)

Download the provided dataset and load it into the created tables. You can use
any utility for this purpose. Using individual insert queries for each row is not
allowed (and possible) for the given dataset. Learn Data Loading from Excel sheet
into SQL server by yourself. It is very easy to learn and use. You have to
understand the type of data in a column while designing the schema. You can
assume empty cells as NULL.





PART#3 – Queries (150 Marks)
Write SQL Queries to retrieve following information:
EASY [5*5=25]
1. All the players that have played under a specific manager.
2. All the matches that have been played in a specific country.
3. All the teams that have won more than 3 matches in their home stadium.
(Assume a team wins only if they scored more goals then other team)
4. All the teams with foreign managers.
5. All the matches that were played in stadiums with seating capacity greater
than 60,000.
MEDIUM [5*10=50]
6. All Goals made without an assist in 2020 by players having height greater
than 180 cm.
7. All Russian teams with win percentage less than 50% in home matches.
8. All Stadiums that have hosted more than 6 matches with host team having
a win percentage less than 50%.
9. The season with the greatest number of left-foot goals.
10. The country with maximum number of players with at least one goal.
HARD [5*15=75]
11.All the stadiums with greater number of left-footed shots than right-footed
shots.
12.All matches that were played in country with maximum cumulative stadium
seating capacity order by recent first.
13.The player duo with the greatest number of goal-assist combination (i.e.
pair of players that have assisted each other in more goals than any other
duo).
14. The team having players with more header goal percentage than any other
team in 2020.
15. The most successful manager of UCL (2016-2022).




BONUS [10]
16. The winner teams for each season of UCL (2016-2022).

Note: You have to retrieve complete information for each query. For example,
when retrieving players that satisfy a specific criterion, you need to retrieve their
first name, last name, DOB, and nationality. Only ID won’t be sufficient. The Same
is the case for all other queries. Also, the queries must be generic and should also
work for different values than those specified in the above queries. This will be
strictly evaluated during demos. The bonus will only be adjusted in this
assignment and won’t be carried forward to any other assessment item.

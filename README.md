# Flipkart-app

## TABLE:SAMPLE
| ID | TEST PREPARATION BOOKS | PRICE  | POPULARITY | DATE |
| -- | -- | -- | -- | -- |
| 1 |  Medical Preparation Books  |  1499  | 3 | 01-01-2019 |
| 2 |  Engg Preparation Books  |  1299  | 2 | 03-01-2019 |
| 3 |  TNPSC Preparation Books  |  499  | 4 | 10-01-2019 |
| 4 |  CAT Preparation Books  |  999  | 2 | 20-1-2019 |
| 5 |  JAVA Preparation Books  |  1599  | 5 | 22-1-2019 |

#### TO LIST ALL BOOKS
select * from sample;
#### TO SORT BOOKS IN ORDER
select * from sample order by TEST PREPARATION BOOKS;
#### TO SELECT AND VIEW PARTICULAR,BOOK'S PARTICULAR
select TEST PREPARATION BOOKS from sample where TEST PREPARATION BOOKS=Medical Preparation Books order by Medical Preparation Books;
#### TO SELECT BOOKS BY ITS PRICE
select price,min(price),max(price) from sample where min(price)>=450 and max(price)<=1600 order by price;
#### TO SELECT BOOKS BY POPULARITY
select POPULARITY from sample where POPULARITY=3 order by POPULARITY;
#### TO SELECT BOOKS BY NEWEST
select DATE from sample order by DATE desc;

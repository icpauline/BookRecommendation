# Book Recommendation
## Introduction
Book Rent is the largest online and offline book rental chain in India. They provide books of various genres, such as thrillers, mysteries, romances, and science fiction. The company charges a fixed rental fee for a book per month. Lately, the company has been losing its user base. The main reason for this is that users are not able to choose the right books for themselves. The company wants to solve this problem and increase its revenue and profit. 
## Task:
You, as an ML expert, should focus on improving the user experience by personalizing it to the user's needs. You have to model a recommendation engine so that users get recommendations for books based on the behavior of similar users. This will ensure that users are renting the books based on their tastes and traits.
## Dataset:
### BX-Users: It contains the information of users.
  - user_id - These have been anonymized and mapped to integers
  - Location - Demographic data is provided
  - Age - Demographic data is provided
### BX-Books: 
  - isbn - Books are identified by their respective ISBNs. Invalid ISBNs have already been removed from the dataset.
  - book_title
  - book_author
  - year_of_publication
  - publisher
### BX-Book-Ratings: Contains the book rating information. 
  - user_id
  - isbn
  - rating - Ratings (`Book-Rating`) are either explicit, expressed on a scale from 1–10 (higher values denoting higher appreciation), or implicit, expressed by 0.
## Approach:
1.	Imported all the three datasets.
2.	Performed data cleaning
3.	Found the unique number of users and books
4.	Converted ISBN to numeric value in the correct order
5.	Converted user_id to numeric value in the correct order
6.	Sorted both ISBN and user_id
7.	Re-indexed columns to build a matrix
8.	Made predictions based on the user and item variable
9.	Evaluated the algorithm using Root Mean Square Error and it is 7.61

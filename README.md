# Hackerrank_restassured
Solving the Hackerrank_problem using rest assured


**URL :** https://jsonmock.hackerrank.com/api/moviesdata/search/?Title=[substr]

**Problem Statement :**
Write a call to an https get method to retrieve information from a movie database concerning how many movies have a particular string in their title.
given a search term, query

The response is a JSON object with the following 5 fields:

page: The current page of the results. (Number)
per_page: The maximum number of results returned per page. (Number)
total: The total number of results. (Number)
total_pages: The total number of pages with results. (Number)
data Either an empty array or an array with a single object that contains the movie details.

Output: the function will return the integer value found in the total in the returned JSON object

**Solution :**

**Using Postman:**

![Screenshot 2023-08-14 at 10 25 31 AM](https://github.com/himani110/Hackerrank_restassured/assets/7402850/75527f94-1409-4c08-bcf7-e3ed9e1e9368)

so the Function should return int value as 1.

**Coding n Automation :**
I have implemented above scenario using both rest assured and http and https packages.
Consider File : RestAssured_implementation_Case1
Consider File : https_connection_Case2.

**Testing:**
Below are the sample test case and their expected results:
Sample Case #	Search string	result
1	don	6
2	harry	226
3	stone	3
4	none	0



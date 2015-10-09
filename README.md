# Coauthored_By
Your task is to write a program in java that  
 Can read the content from the file (preferably line wise)
 For given pair of authors in the test cases, it should return the title of the article(s) that is/are co-authored by them. o
So your method(called coauthored) should take two strings as the arguments- author1 and author2 o 
The return type of your function should be an ArrayList of String which contains the Title of the articles co-authored by the pair. 
If no such article exists then return an empty arraylist.
1. You have been provided with a csv file that contains the details of a number of articles. 
2. The format of CSV FILE: Author Name,Paper Title,Journal Name,Year of Publication 
3. Assume that ‘,’ is only used as a separator and nowhere else 
4. Make sure that the path of the file while reading is set to this: ./src/output.csv 
5. This implies, place the provided csv file directly in the src folder of your project 
6. You have been provided with a JUnit test file to test your program 
7. You have been provided with javadoc for Hashmap, in case you need help. 

Imagine it as a mapping relation from a set of Authors to set of Articles and for given pair of authors check their mapping to set of 
 Articles to look out for common article.
 (Hint: You could use ArrayList or Hashmap to maintain such relation, however it is upto to you if you want to make use of any collection)
 You have already worked extensively with ArrayList, however, if you need help with using Hashmap.Design your program such that is passes these tests.  

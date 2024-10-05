# Book-analysis-case-study-
Book analysis case study contains the dataset that is analyzed using excel functions

Recently, I worked on a book analysis case study, leveraging a dataset that included fields such as bookID, title, authors, average_rating, isbn, language_code, num_pages, ratings_count, text_reviews_count, and publication_date. This project allowed me to apply various Excel functions to gain insights into book ratings and other characteristics.

One of the key analyses involved creating a condition using the IF function. I set up a rule that if the book's rating was greater than 4, the function would return "Highly Recommended," giving a quick overview of top-rated books. I also verified whether all book titles were in text format using Excel's ISTEXT function.

For a specific book with bookID 85, I used the VLOOKUP function to retrieve the corresponding ratings, allowing me to focus on the performance of individual titles. Additionally, I worked with text extraction functions to manipulate titles. For example, I extracted the first and last 5 characters from the title of Harry Potter using the LEFT and RIGHT functions.

To handle language codes in the dataset, I used the SWITCH function to return the full name of the language based on the language code. This simplified the analysis by converting coded data into meaningful information.

Filtering the dataset for Harry Potter books was another important task. I applied filters to focus on this specific series and examine its ratings and reviews. To further explore the structure of book titles, I extracted characters from the middle of titles using the MID function and displayed the length of each title using the LEN function.

Finally, I created a pivot table to summarize the data, displaying the titles along with the sum of their ratings. This helped to visualize how different books performed in terms of ratings and provided a clearer understanding of their overall reception.

This case study was a great opportunity to refine my skills in Excel, particularly with text functions, logical conditions, and pivot tables. It showcased how Excel can be a powerful tool for analyzing large datasets and drawing meaningful conclusions.

# **Book-Recommendation**

This is a book recommendation project that offers 3 algorithms for book recommendations. Each algorithm is designed to cater to different user scenarios and purposes.

## **Algorithms**

1. **Popular Books Algorithm**: This algorithm is best suited for new users or individuals who haven't read many books or don't have specific preferences. It identifies books with the highest weighted ratings and suggests them as popular recommendations.

2. **Content-Based Filtering Algorithm**: This lgorithm analyzes the characteristics of books, such as title, author, and publisher, to recommend similar books. It matches user preferences with book attributes and suggests relevant titles.

3. **Collaborative Filtering (Item-Based) Algorithm**: The item-based collaborative filtering algorithm identifies patterns in user ratings and recommends books that users with similar tastes have enjoyed. It explores relationships between books and suggests items based on user-item similarity.


## **How to Use**

To use the book recommendation algorithms, follow these steps:
- Clone the repository to your local machine.
- Install the necessary dependencies.
- Run all the cells. 
- Run the desired algorithm function and change the corresponding input.

## **Comparison**

The table below summarizes the pros and cons of each algorithm, as well as the recommended scenarios for their usage:


|   Algorithm  | Pros | Cons | Recommend Usage|
| --- | --- | --- | --- |
| Popular Books| Easy to implement <br><br> Straightforward    | Limited personalization| New users or individuals without specific preferences|
| Content-Based Filtering| Can recommend books of same genres, similar styles  | Limited to available content attributes <br><br> Cannot suggest something really different from genres the user has read | Users with specific preferences or book attributes |
| Collaborative Filtering    | Can recommend books from different genre to user | Required more past ratings from users for better recommendation      | Users that want to read something new |


Choose the algorithm that aligns with your users' characteristics and your project goals. Consider the pros and cons listed above to determine the most suitable algorithm for your specific book recommendation needs.

## **Future work**

There are still many areas for improvements. Some possible areas to explore include:

* Content-Based Filtering: Incorporating additional book attributes, such as synopsis or genres, to improve the accuracy of content-based recommendations.
* User-Based Collaborative Filtering: Exploring user-based collaborative filtering to leverage user similarity and provide more personalized recommendations.
* Hybrid Approaches: Investigating hybrid approaches that combine multiple algorithms to provide more robust and accurate recommendations.
* Evaluation Metrics: Developing evaluation metrics to measure the performance and effectiveness of the recommendation algorithms.

## **License**

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code for your own purposes.

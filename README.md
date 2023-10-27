# Rating-Product-Sorting-Reviews-in-Amazon
The aim is to evaluate the given ratings by weighting them according to the date and comparing the "initial average rating" with the "weighted rating based on the date" to be obtained.  Then, the reviews will be sorted.

BUSINESS PROBLEM
One of the most significant challenges in e-commerce is the accurate calculation of post-purchase ratings for products.

Solving this problem means providing more customer satisfaction for e-commerce websites, better product visibility for sellers, and a seamless shopping experience for buyers.

Another challenge is the proper sorting of product reviews.

The prominence of misleading reviews can directly impact product sales, leading to both financial loss and customer attrition.

The resolution of these two fundamental issues will result in increased sales for e-commerce platforms and sellers, as well as a smooth shopping journey for customers.


ABOUT DATASET
Content: This dataset containing Amazon product data includes product categories along with various metadata.

Context: The product with the most reviews in the Electronics category has user ratings and reviews.

COLUMNS

reviewerID: User ID
asin: Product ID
reviewerName: Username
helpful: Helpful review rating
reviewText: Review
overall: Product rating
summary: Evaluation summary
unixReviewTime: Review time
reviewTime: Review time Raw
day_diff: Number of days since evaluation
helpful_yes: Number of times the review was found helpful
total_vote: Number of votes cast on the review



TASK
In the shared dataset, users have provided ratings and reviews for a product. The aim is to evaluate the given ratings by weighting them according to the date and comparing the "initial average rating" with the "weighted rating based on the date" to be obtained.
Then,the reviews will be sorted.


RESULT
In summary, when considering the "wilson_lower_bound" proves to be a more accurate measure of ranking success. For instance, when examining the reviews with indices such as 4072, 1072, 2583, or 121, it becomes evident that there are no negative comments, but the count of positive reviews is significantly low. As a result, the score_average_rating of 1 may present a biased perspective. In contrast, the wilson_lower_bound takes into consideration both helpful feedback and review frequency.



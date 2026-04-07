# Paint Data Analysis

## Project Overview
This project involves an exploratory data analysis (EDA) of Amazon paint product data. The goal is to uncover insights into product pricing, ratings, review counts, and brand performance. The analysis helps in understanding market trends, customer sentiment, and competitive landscapes within the paint product category on Amazon.

## Dataset
The analysis utilizes a dataset named `amazon_paint_data.csv` which contains information about various paint products listed on Amazon. Key columns include:
- `title`: Product title
- `price_raw`: Original price string
- `price_num`: Numerical price for analysis
- `rating_num`: Numerical product rating
- `reviews_num`: Number of reviews
- `base_type`: Type of paint base (e.g., 'Oil', 'Water')
- `brand`: Product brand

## Methodology
The project follows a standard EDA approach:
1.  **Data Loading**: The `amazon_paint_data.csv` file is loaded into a pandas DataFrame.
2.  **Price Distribution Analysis**: A histogram is generated to visualize the distribution of product prices.
3.  **Rating Analysis**: 
    *   A histogram shows the distribution of product ratings.
    *   A bar plot illustrates the average rating by paint base type.
4.  **Review Count vs. Rating**: A scatter plot explores the relationship between the number of reviews and product ratings.
5.  **Brand Performance Analysis**: 
    *   Top 10 brands (by product count) are identified.
    *   Bar plots display the average price, average rating, and average review count for these top brands.
6.  **Paint Type Comparison**: Box plots compare price and rating distributions across different paint base types.
7.  **Color Palettes**: Custom color palettes ("green tea" and "sophisticated red") were applied to the visualizations to enhance aesthetics and improve readability.

## Key Insights
-   **Price Distribution**: Most paint products fall within a specific price range, with fewer products at extreme high or low prices.
-   **Rating Trends**: The majority of products receive high ratings, indicating general customer satisfaction, though some variation exists across base types.
-   **Reviews and Ratings**: A positive correlation might exist between the number of reviews and ratings, suggesting that popular products tend to be well-regarded.
-   **Brand Performance**: Significant differences in average prices, ratings, and review counts were observed among top brands, highlighting varying market positions and customer perceptions.
-   **Base Type Comparison**: Different paint base types show distinct price and rating distributions, which could inform product strategy or market segmentation.

## Benefits
This analysis provides valuable insights for:
-   **Product Strategy**: Identifying popular price points, well-received product features, and high-performing brands can guide new product development.
-   **Marketing Campaigns**: Understanding customer sentiment and rating distribution can inform targeted marketing efforts.
-   **Competitive Analysis**: Benchmarking brand performance helps in assessing the competitive landscape and identifying areas for improvement.
-   **Customer Understanding**: Gaining insights into what drives positive ratings and review engagement can help improve overall customer satisfaction.

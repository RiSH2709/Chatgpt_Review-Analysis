## ChatGPT Review Analysis 📊

This repository contains a Python-based project focused on analyzing **ChatGPT user reviews** to uncover key insights about user sentiment and satisfaction. The project includes various data analysis techniques such as **sentiment analysis**, **common phrase extraction**, and **Net Promoter Score (NPS) calculation**. Visualizations are created using **Plotly** to display trends and patterns in the data.

### Files:
- **chatgpt_review.py**: A Python script for data cleaning, sentiment analysis, and generating visualizations.
- **chatgpt_reviews.xlsx**: An Excel file containing the raw user review data used for analysis. It includes columns for ratings, comments, and timestamps.

### Visualizations:
- **Sentiment Distribution**: A bar plot showcasing the breakdown of positive, negative, and neutral sentiments in the reviews.
- **Top Positive & Negative Phrases**: Horizontal bar charts highlighting common phrases from both positive and negative reviews.
- **Common Problems Faced by Users**: A bar chart visualizing the most frequently mentioned issues reported by users.
- **Sentiment Trends Over Time**: A line chart illustrating how sentiment changes over different time periods based on review dates.

### Net Promoter Score (NPS):
The NPS score, calculated based on user ratings, helps gauge user loyalty and satisfaction. In this project, the NPS was calculated using the assumption that 5-star reviews are **Promoters**, 4-star reviews are **Passives**, and 3-star (or below) reviews are **Detractors**. The final NPS score is approximately **64.35**, indicating a strong likelihood that users would recommend ChatGPT to others.

### How This Can Benefit Companies:
This type of review analysis provides companies with actionable insights from customer feedback. By leveraging sentiment analysis, companies can:
- **Identify product strengths**: Pinpoint features users appreciate most, guiding future improvements and marketing strategies.
- **Address pain points**: Highlight common user complaints or issues, enabling prompt resolution to enhance customer experience.
- **Track trends**: Understand how sentiment changes over time, providing a feedback loop to monitor the effectiveness of product updates or customer support efforts.
- **Measure customer loyalty**: The NPS score helps businesses gauge user satisfaction and predict future recommendations, a key metric for growth.

### How to Use:
1. Clone or download the repository.
2. Load the `chatgpt_reviews.xlsx` dataset.
3. Run the `chatgpt_review.py` script to perform sentiment analysis and generate visualizations.
4. Explore the insights and visualizations to understand user sentiment and feedback.


### Conclusion:
By analyzing customer reviews, this project provides valuable insights for businesses looking to improve products, measure user satisfaction, and fine-tune their strategies based on real user data. The analysis can be easily adapted to any other product or service, making it a useful tool for ongoing customer feedback analysis.

Feel free to fork this repository, contribute improvements, or use it for your own analysis!

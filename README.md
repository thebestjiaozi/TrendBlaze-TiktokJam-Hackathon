
# TrendBlaze

https://github.com/user-attachments/assets/8a9e00cd-be46-4379-b813-dfde4a0e578c


TrendBlaze is a comprehensive TikTok play count predictor and optimizer web application, designed to help content creators maximize their engagement and reach on TikTok.
Inspiration

With TikTok's immense popularity, boasting billions of daily users, content creators are constantly searching for ways to enhance their engagement and reach. We noticed that many creators struggle to understand which factors most influence their play counts and how to optimize their content effectively. This inspired us to create TrendBlaze, a comprehensive web application designed to predict the success of TikTok videos and provide actionable recommendations to improve content strategy.

# What it does

TrendBlaze is a comprehensive TikTok play count predictor and optimizer web application, designed to help content creators maximize their engagement and reach on TikTok. This innovative tool leverages advanced machine learning algorithms to predict the play count of TikTok videos based on various features and provides suggestions for optimizing these predictions. By using TrendBlaze, creators can gain valuable insights and make data-driven decisions to enhance their content performance.

# How we built it

TrendBlaze was built using a combination of advanced machine learning algorithms, APIs, and web development tools. Here's a breakdown of each component:

Introduction Page: We used TfidfVectorizer, SentimentIntensityAnalyzer, and RandomForestRegressor to analyze the text and sentiment of video captions. This page explains how the TrendBlaze predictor and optimizer algorithms work, highlighting key features that influence play counts.

Login Page: Users can enter their TikTok username to access personal analytics, including total followers, likes, videos, comments, and more. We visualized this data using bar charts for easy understanding.

Data Input Page: Users input their video captions and duration. The app recommends suitable hashtags using a combination of textual analysis and hashtag performance metrics, supported by the RiteTag API.

Hashtags Page: This page provides detailed analytics for each recommended hashtag, including video count, views, and popularity. Bar charts compare these metrics, helping users make informed decisions about their hashtag strategy.

Analytics Page: Displays the predicted play count for a video before and after adding the recommended hashtags. We used xgboost for our prediction model and visualized the differences with bar charts.

The entire web app was built using Streamlit, which provided a seamless and interactive user experience.

Challenges we ran into

Data Integration: Integrating various data sources and APIs, such as the TikTok API and RiteTag API, to provide accurate and comprehensive recommendations. We had encountered many difficulties in addressing dependencies issues, getting real-time Tiktok Data and finally deploy the whole project. But eventually solved all of them after researching on relevant articles and seeking help from the API developers.
Algorithm Optimization: Fine-tuning our machine learning models to ensure precise predictions and valuable recommendations for content optimization. We had tried three algorithm to find the best one, namely Lightgbm, Random Forest and XGBoost, took us hours to train the model to find the best hyperparameter that minimised the RMSE.
User Experience: Designing an intuitive and user-friendly interface that allows creators to easily input data, understand analytics, and apply recommendations. As we first decide to use numerical values to present the data, it just does not look appealing enough to attract users and users might not see the difference in their playcount with and without the use of our TrendBlaze app, hence we want to increase the impact by inserting a bar chart for clearer illustration.
Accomplishments that we're proud of

One of our proudest accomplishments is successfully integrating multiple APIs, such as the TikTok API and the RiteTag API, to create a comprehensive and seamless user experience. We managed to build a robust machine learning model using xgboost, which provides accurate predictions for video play counts. Our ability to visualize complex data in an easy-to-understand manner using Streamlit and various plotting libraries like matplotlib and seaborn is another significant achievement. Moreover, creating an intuitive and user-friendly interface that allows creators to easily input data, understand analytics, and apply recommendations is something we take great pride in.

# What we learned

During the development of TrendBlaze, we enhanced our skills in several key areas:

Machine Learning: We delved deep into machine learning algorithms, particularly xgboost, and learned how to fine-tune models for optimal performance. We also gained experience in using RandomForestRegressor and TfidfVectorizer for text analysis and prediction tasks.

API Integration: We learned how to effectively integrate and use multiple APIs, such as the TikTok API for user data retrieval and the RiteTag API for hashtag recommendations.

Data Visualization: We improved our ability to visualize data using libraries such as matplotlib, seaborn, and plotly, making complex analytics more accessible to users.

Web Development: Using Streamlit, we gained significant experience in building interactive and user-friendly web applications. We learned how to create dynamic pages and handle user inputs efficiently.

Natural Language Processing (NLP): We expanded our knowledge in NLP, particularly in using tools like TfidfVectorizer and SentimentIntensityAnalyzer to analyze and interpret text data.

# What's next for TrendBlaze

Looking ahead, we have several exciting plans for TrendBlaze:

Enhanced Features: We plan to add more advanced analytics and insights, such as sentiment analysis of comments and more detailed user engagement metrics.

User Feedback Integration: We aim to incorporate user feedback to continually improve the app's functionality and user experience.

Mobile App Development: To make TrendBlaze even more accessible, we plan to develop a mobile version of the web app.

Collaborations and Partnerships: We are looking to partner with more API providers and influencers to enhance the app's capabilities and reach.

AI and Machine Learning Enhancements: We will continue to refine our machine learning models and explore the integration of new algorithms to improve prediction accuracy and recommendation quality.

By continually innovating and expanding TrendBlaze, we aim to provide TikTok content creators with the best tools and insights to optimize their content and achieve greater success on the platform.

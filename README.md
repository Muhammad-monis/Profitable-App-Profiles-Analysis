Data Analysis: Profitable App Profiles for App Store and Google Play Markets
📌 Project Overview
The objective of this project is to identify mobile app profiles that are profitable for both the App Store and Google Play markets. Acting as a data analyst for a mobile app development company, the goal is to provide data-driven recommendations to help developers build apps that attract a high number of users, thereby maximizing revenue from in-app advertisements.

🛠️ Tech Stack & Skills
Language: Python 3

Libraries: csv (for data ingestion), NumPy, Pandas (conceptually applied)

Concepts: Data Cleaning, String Manipulation (ASCII filtering), Frequency Tables, Data Transformation, and Proxy Metrics

📂 Dataset Information
This analysis utilizes two primary datasets to capture the landscape of the app market as of September 2018:

Google Play Store Data: ~10,000 Android apps.

App Store Data: ~7,000 iOS apps.

🔍 Data Cleaning & Preprocessing
A significant portion of this project involved rigorous data cleaning to ensure the reliability of the results:

Removing Erroneous Data: Identified and deleted rows with missing or shifted values (e.g., the "Life Made WI-Fi Touchscreen Photo Frame" entry).

Handling Duplicates: Implemented logic to remove duplicate entries by keeping only the row with the highest number of reviews, ensuring we used the most recent data point for each app.

Language Filtering: Developed a custom is_english() function using ASCII character encoding to filter out non-English apps.

Isolating Free Apps: Filtered the data to include only free-to-download apps, aligning the analysis with the company's business model.

📈 Key Insights & Findings
Genre Frequencies: The App Store is heavily dominated by "Games" (58.16%), while Google Play shows a more balanced mix of "Family," "Tools," and "Games".

Popularity Proxy: Because the App Store lacks install data, "Total User Ratings" was used as a proxy for popularity.

Market Opportunity: While genres like "Social Networking" and "Navigation" have high average installs/ratings, they are dominated by a few industry giants. The "Books and Reference" genre was identified as a niche with significant potential for growth on both platforms.

💡 Final Recommendation
The analysis suggests developing a Reference/Book-based application. By taking existing book content and adding interactive features like daily quotes, audio versions, and integrated dictionaries, the company can stand out in a market currently saturated with "for-fun" apps.# Profitable-App-Profiles-Analysis

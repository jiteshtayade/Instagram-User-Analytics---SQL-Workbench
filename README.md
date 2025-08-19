# Instagram-User-Analytics---SQL-Workbench
Project Overview
-- This project explores Instagram user behavior and platform engagement using SQL. The analysis focuses on understanding loyal users, inactive accounts, popular content, and usage patterns. It was designed to simulate real-world marketing and investor metrics that businesses track for growth.

Dataset
- The project uses multiple relational tables:
1. users → user_id, username, created_at
2. photos → photo_id, user_id, image_url
3. likes → user_id, photo_id, created_at
4. comments → comment_id, user_id, photo_id, created_at, text
5. tags → tag_id, tag_name
6. photo_tags → photo_id, tag_id
7. follows → follower_id, followee_id, created_at
Dataset size: ~100 users, photos/likes/comments under 100 each (small but relationally rich).

Tech Stack
- SQL Workbench – Querying and data analysis
- MySQL – Database engine

Key Analyses Performed
- Marketing Analysis
- Loyal User Reward → Identified the 5 oldest Instagram users.
- Inactive User Engagement → Found users who never posted a photo.
- Contest Winner Declaration → Determined the user with the most likes on a single photo.
- Hashtag Research → Suggested the top 5 most commonly used hashtags.
- Ad Campaign Launch → Determined the most popular weekday for user sign-ups.

Investor Metrics
- User Engagement → Calculated the average number of posts per user and overall posting ratio.
- Bots & Fake Accounts → Flagged potential bot users who liked every single photo.

SQL Concepts Applied
- Joins (INNER, LEFT, SELF JOIN)
- Aggregations (COUNT, SUM, MAX)
- Window Functions (ROW_NUMBER, RANK)
- Subqueries & Nested SELECTs
- Date/Time Functions (DAYNAME, WEEKDAY)
- Grouping & Filtering (GROUP BY, HAVING)

Insights Gained
- Identified the most loyal and inactive user groups, valuable for targeted marketing.
- Detected fake-like behavior, an indicator of bot activity.
- Discovered most popular hashtags, useful for brand partnerships.
- Suggested best ad campaign day based on sign-up trends.

# Youtube_trending_videos
SQL Project: YouTube Trending Videos

## Introduction
YouTube’s trending videos vary by location across the world. The impact of likes, dislikes, comments may differ based on the countries. The demographics of countries itself is a big factor in the way videos are consumed in various countries. The videos can be trending if video views are above a certain level. This is an analysis how average trending periods of videos vary across countries. How the likes, dislikes, comments impact the duration of trending videos. Exploring some interesting insights from the data which could be done through exploratory data analysis.

* [Data Analysis Question & Answers](https://github.com/KopiteArnab/Youtube_trending_videos/blob/bb5c3d1ed9f22ac0acebd2a8962750e2869e7bc1/questions_and_answers.md)

## Datasets used
There are 3 tables available for the analysis
- [YT_trending_videos.csv](https://github.com/KopiteArnab/Youtube_trending_videos/blob/c8c87558b1ea721eeec5486c1ee2ede522a0c71f/YT_trending_videos.csv):    YT_trending_videos: This table has video level information along with dates on which videos were trending along with metrics such as comments, likes, views, etc.
- [YT_channel_map.csv](https://github.com/KopiteArnab/Youtube_trending_videos/blob/e99b1c3685945bdd561af0e1aaf6e056a4357d65/YT_channel_map.csv):
YT_channel_map: This table has channel_id mapping with the channel title which is also interpreted as channel name
- [YT_category_map.csv](https://github.com/KopiteArnab/Youtube_trending_videos/blob/7cca3a96b3996726f647bfaa511e644eb77ab78f/YT_category_map.csv):
YT_category_map: This table has category_id mapping. The videos on YouTube are mapped to a category based on the type of video such as Movie, trailer, animation, etc.

## Data Dictionary

#### YT_trending_videos
![sqlp1](https://user-images.githubusercontent.com/93368813/210611558-2e8a416a-bdd6-4c77-a01e-8ef9c2b5919b.png)
#### YT_channel_map
![sqlp2](https://user-images.githubusercontent.com/93368813/210611795-280cd92c-3a47-48db-b029-8f69d0b401db.png)
#### YT_category_map
![sqlp3](https://user-images.githubusercontent.com/93368813/210611875-aead0f56-1d93-4ea9-a78a-8307018e10a4.png)


## Entity Relationship Diagram
![alt text](https://github.com/KopiteArnab/Youtube_trending_videos/blob/c8c87558b1ea721eeec5486c1ee2ede522a0c71f/ERD.jpg)

# Course 6 End-of-course project: Classifying videos using machine learning

In this project, I will practice using machine learning algorithms including XGBoost and Random Forest to predict whether a TikTok video presents a "claim" or an "opinion".

The purpose of this model is to increase response time and system efficiency by automating the initial stages of the process of identifying claims.

### Data dictionary

This project uses a dataset called `tiktok_dataset.csv`. It contains synthetic data created for this project in partnership with TikTok.

The dataset contains:

- 19,383 rows – Each row represents a different published TikTok video in which a claim/opinion has been made.
- 12 columns

| Column name               | Type | Description                                                                                                  |
|---------------------------|------|--------------------------------------------------------------------------------------------------------------|
| #                         | int  | TikTok assigned number for video with claim/opinion.                                                         |
| claim_status              | obj  | Whether the published video has been identified as an "opinion" or a "claim."                                |
| video_id                  | int  | Random identifying number assigned to video upon publication on TikTok.                                      |
| video_duration_sec        | int  | How long the published video is measured in seconds.                                                         |
| video_transcription_text  | obj  | Transcribed text of the words spoken in the published video.                                                  |
| verified_status           | obj  | Indicates the status of the TikTok user who published the video in terms of their verification.               |
| author_ban_status         | obj  | Indicates the status of the TikTok user who published the video in terms of their permissions.                |
| video_view_count          | float| The total number of times the published video has been viewed.                                               |
| video_like_count          | float| The total number of times the published video has been liked by other users.                                 |
| video_share_count         | float| The total number of times the published video has been shared by other users.                                |
| video_download_count      | float| The total number of times the published video has been downloaded by other users.                            |
| video_comment_count       | float| The total number of comments on the published video.                                                         |

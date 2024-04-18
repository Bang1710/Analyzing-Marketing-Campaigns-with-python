## Analyzing Marketing Campaigns with Python
![separator1](https://i.imgur.com/ZUWYTii.png)

### About the Dataset

| Column | Description |
|:--------------------------|:--------------------------------------------------|
| user_id | This is a unique number or string that represents each user in your system. |
| date_served | The date on which a particular marketing campaign was shown to the user. |
| marketing_channel | The marketing channel used to deliver that advertisement or marketing campaign (e.g., online advertising, email, social media). |
| variant | Specific variation or version of that marketing campaign. |
| converted | A boolean column indicating whether the user converted (took the desired action, such as making a purchase) after being exposed to that marketing campaign. |
| language_displayed | The language displayed to the user. |
| language_preferred | The user's preferred language. |
| age_group | The user's age group. |
| date_subscribed | The date on which a user signed up for a service or product after being exposed to a marketing campaign. |
| date_canceled | The date the user canceled their subscription to the service or product (if applicable). |
| subscribing_channel | The channel the user used to sign up for the service or product. |
| is_retained | A boolean column indicating whether the user has been retained after a certain period of time. |
| DoW | The day of the week on which the user is registered. |
| channel_code | The code representing the channel the user used to subscribe. |
| is_correct_lang | A column indicating whether the displayed language and the user's preferred language match. |

### Project Overview
This project utilizes marketing campaign data to answer business questions such as "How effective is this campaign?", "Which channel drives the most sign-ups?", "Why is a specific channel underperforming?" The project focuses on measuring conversion rates and retention rates across different marketing channels, as well as analyzing differences among age groups and displayed languages.

### Analysis Highlights
The analysis includes various aspects of marketing campaign performance, including:

- User interaction and conversion rates by marketing channel.
- Effectiveness of different variants of the campaign.
- Language preferences and their impact on conversions.
- Demographic statistics on age groups and retention rates.
- Trends in day-of-week registration and conversion rates.
- Performance of channels and language suitability for users.
For detailed analysis and insights, please refer to the provided Jupyter Notebook or script.

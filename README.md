# DSA210 Project Proposal
Ömer Rıfat Kuldaşlı

## Overview
The goal of this project is to analyse my personal usage data from several online platforms between 2018 and 2026 and identify potential patterns in this data. These patterns may include recurring time-based changes in usage (for example, during certain seasons or after a certain year). The data also includes text content of my messages and posts, so perhaps the average length of my content may have changed over the years. The data may also be affected by certain external events (COVID-19, access restrictions in Turkey, etc.), so these events will be taken into consideration as well.

## Data Sources
| Name | Data Range | Contents | Collection Method |
| --- | --- | --- | --- |
| Personal Reddit Data |2018-2026 | Post and comment data (timestamp, subreddit, text content) | Data request |
| Liked Reddit Post Data | Varies | Post and comment data (timestamp, subreddit, text content) | API requests, webscraping |
| Personal Discord Data | 2018-2026 | Messages (timestamp, server, channel, text content) | Data request |
| Personal GitHub Data | 2018-2026 | Commit history, issues, pull requests, issue comments (timestamp, repository, text content) | Data request, API requests |
| Personal X (Twitter) Data | 2018-2026 | Tweet contents, likes, bookmarks (timestamp, text content) | Data request |
| Liked X (Twitter) Post Data | Varies | Tweet contents (timestamp, text content) | API requests, webscraping |

Most of the data I need can be requested directly from the respective platforms as JSON and CSV files. However, there is some data that is not provided as part of this data, such as the details of liked or bookmarked posts. These parts of the data may require additional API requests and web scraping to retrieve. Some of these posts or comments may have been removed as well, so retrieving some data may require relying on archived data like dumps on the Web Archive.

# GitHub User Data Insights- 
Anupama Manjunath IITM DS TDS Project 1

Summary (TLDR): Used Python to scrape user data from the GitHub API, targeting Zurich-based users with over 50 followers. Extracted key details such as usernames, company affiliations, and repository information, storing the data in CSV files. Performed Exploratory Data Analysis (EDA) to identify top users, popular programming languages, and most-used Git licenses etc.

**1. Data Scraping:**
I used Python to scrape user data from the GitHub API by sending HTTP GET requests. The process involved retrieving users located in Zurich with over 50 followers, parsing the JSON responses to extract relevant fields like usernames, company affiliations, and repository details, and saving the data in CSV files for analysis.

**2. Interesting Fact**: 
I wanted to find out- "How does the number of followers relate to the length of time a user has been on GitHub?" Surprisingly, the regression analysis shows no significant correlation between GitHub account age and follower count, with an R-squared value of 0, low F-statistic (0.002365) with a p-value of 0.961. This indicates that relationship between account age and follower count is not statistically significant and other factors likely influence follower growth beyond the duration of account existence. (see image below) 

**3. Actionable Reccomendation based on previous analysis:**
Developers should prioritize actively engaging with the GitHub community by contributing to popular open-source projects, participating in discussions, and collaborating with others. Additionally, sharing knowledge through blog posts, tutorials, or talks can enhance visibility and attract followers, regardless of the duration of their account. Regularly updating repositories and interacting with followers can also foster a sense of community and encourage more users to follow.



[image](https://github.com/user-attachments/assets/40b9ac54-fc59-4699-9548-012f2768d084)
<img width="466" alt="image" src="https://github.com/user-attachments/assets/753442d1-336a-4e06-a512-0fdd1710ce62">








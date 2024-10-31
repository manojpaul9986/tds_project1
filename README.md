- I used Python's aiohttp library to scrape user and repository data from the GitHub API asynchronously. The script sends HTTP requests to fetch users in Chicago with over 100 followers and gathers details such as their names, companies, locations, and repositories. The final output consists of two CSV files: **"users.csv"**, containing user profiles such as their username, company,  etc, and **"repositories.csv"**, listing their associated repositories along with relevant details like stargazer count and programming language. This approach allows for efficient data retrieval while handling potential errors gracefully.
- After analyzing the user and repository data extracted from GitHub, several key insights emerged:

     **Most Popular Licenses**: The top three licenses favored by developers include the MIT License, Other, and the Apache License 2.0, along with the BSD 3-Clause "New" or 
                               "Revised" License.

     **Predominant Company**: A significant number of developers are affiliated with the University of Chicago, which stands out as the company employing the majority of these 
                              users.

     **Dominant Programming Language**: JavaScript was identified as the most popular programming language among the analyzed users, reflecting current industry trends.

     **Highest Average Stars**: Vim Script emerged as the programming language associated with the highest average number of stars per repository, boasting an impressive 
                                average of 647.45 stars.

     **Positive Correlation**: The analysis also revealed a positive correlation between the number of public repositories a user has and their follower count, indicating that 
                               greater repository activity can lead to increased visibility and engagement on the platform.
- Based on the analysis, developers should consider prioritizing the use of popular licenses, such as the MIT License and Apache License 2.0, for their open-source projects to enhance collaboration and visibility within the developer community. Additionally, actively engaging in creating public repositories can significantly boost their follower count, leading to greater networking opportunities and professional growth. Developers are also encouraged to stay current with popular programming languages like JavaScript, as this can improve their marketability and relevance in the tech industry. By focusing on these strategies, developers can maximize their impact and presence on platforms like GitHub.

# GitHub User Analysis in Tokyo {Project-1}

## Overview
This project analyzes GitHub users located in Tokyo with over 200 followers. The goal is to extract valuable insights from user profiles and their repositories using the GitHub API.

# -->Data was scraped from the GitHub API by filtering users in Tokyo,Japan with over 200 followers and fetching their most recent repositories.

# -->Majority of the repositories from Tokyo are written in JavaScript but surprisingly Rust is seen in many repositories, mainly newer users. Also, Assembly happens to be the language with highest average stars per repository. Surprising!!!

# -->Developers in Tokyo should focus on collaboration in JavaScript-based and Rust-based projects to leverage the local expertise and community.


## Key Insights
- **Data Extraction**: Utilized the GitHub API to scrape user data and repositories efficiently.
- **User Statistics**: Analyzed the number of followers, repositories, and the most popular programming languages used by developers.
- **Recommendations**: Provided actionable insights based on data analysis to help developers improve their presence on GitHub.

## Methodology
1. **API Usage**: Leveraged the GitHub API to fetch users and their repositories based on specific criteria.
2. **Data Cleaning**: Processed the fetched data to ensure consistency and accuracy.
3. **Statistical Analysis**: Conducted various analyses to derive meaningful insights from the data.

## Project Files
- `users.csv`: Contains detailed information about users from Tokyo with over 200 followers.
- `repositories.csv`: Lists the public repositories of these users, including their attributes.
- `README.md`: This file documenting the project.

## Findings
- **Top 5 Users by Followers**: 
    - `'dennybritz', 'wasabeef', 'dai-shi', 'rui314', 'domenic'`
- **Earliest Registered Users**: 
    - `kana,kakutani,mootoh,lhl,walf443`
- **Most Popular Licenses**: 
    - `mit,apache-2.0,other`
- **Most Common Programming Language**: 
    - `JavaScript`
- **Top Companies**: 
    - `Google`
- **Correlation Analysis**: 
    - Followers and public repositories showed a correlation of `0.051`.
- **Repository Insights**: 
    - Users who created more repositories gained approximately `2.17` additional followers per repository.
## Conclusion
This project highlights the potential of GitHub as a platform for developers to showcase their skills and engage with the community. The insights derived from this analysis can help inform strategies for personal branding and networking on GitHub.


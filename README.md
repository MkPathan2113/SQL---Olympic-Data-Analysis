# Olympics Data Analysis using SQL

## Overview
This repository contains SQL queries for analyzing the Olympics dataset. The analysis covers various aspects such as the number of Olympic Games held, participating countries, top-performing nations, and athlete-specific insights. The dataset consists of two tables:

1. **OLYMPICS_HISTORY** - Contains historical records of Olympic athletes, their events, and medals won.
2. **OLYMPICS_HISTORY_NOC_REGIONS** - Maps National Olympic Committees (NOC) to their respective regions.

## Database Schema

### Table: OLYMPICS_HISTORY
| Column Name | Data Type | Description |
|-------------|----------|-------------|
| id | INT | Unique identifier for each record |
| name | VARCHAR | Athlete's name |
| sex | VARCHAR | Gender of the athlete |
| age | VARCHAR | Age of the athlete |
| height | VARCHAR | Height of the athlete |
| weight | VARCHAR | Weight of the athlete |
| team | VARCHAR | Team/Nation the athlete represents |
| noc | VARCHAR | National Olympic Committee code |
| games | VARCHAR | Olympic Games edition (Year + Season) |
| year | INT | Year of the Olympics |
| season | VARCHAR | Season (Summer/Winter) |
| city | VARCHAR | Host city of the Olympics |
| sport | VARCHAR | Sport category |
| event | VARCHAR | Specific event in the sport |
| medal | VARCHAR | Medal won (Gold, Silver, Bronze, or NA) |

### Table: OLYMPICS_HISTORY_NOC_REGIONS
| Column Name | Data Type | Description |
|-------------|----------|-------------|
| noc | VARCHAR | National Olympic Committee code |
| region | VARCHAR | Country/Region represented |
| notes | VARCHAR | Additional information |

## SQL Queries
This repository contains 20 SQL queries that analyze different aspects of the Olympics dataset. Below is a summary of the key analyses:

1. **Total Olympic Games Held** - Counts the number of Olympic editions.
2. **List of Olympic Games** - Provides a list of all Olympics held, along with their host cities.
3. **Total Nations Participated Per Olympics** - Counts the number of nations in each edition.
4. **Year with Highest & Lowest Participation** - Identifies the Olympics with the most and least participating nations.
5. **Countries That Participated in All Olympics** - Lists nations that never missed an Olympic event.
6. **Sports Played in All Summer Olympics** - Finds sports consistently included in every Summer Olympics.
7. **Sports Played Only Once** - Identifies sports that appeared in only one Olympic edition.
8. **Total Sports Per Olympics** - Counts the number of unique sports in each Olympic edition.
9. **Oldest Gold Medalist** - Finds the oldest athlete to win a gold medal.
10. **Male-to-Female Participation Ratio** - Computes the ratio of male and female athletes across all Olympics.
11. **Top 5 Athletes with Most Gold Medals** - Identifies athletes with the highest gold medal count.
12. **Top 5 Athletes with Most Medals (Any Type)** - Lists athletes with the highest total medals won.
13. **Top 5 Most Successful Countries** - Ranks countries by total medals won.
14. **Total Medals Per Country** - Breaks down gold, silver, and bronze medals won by each nation.
15. **Medals Per Country in Each Olympics** - Lists medals won by each country in every Olympic edition.
16. **Country with Most Medals in Each Olympics** - Identifies nations that won the most gold, silver, and bronze medals per Olympics.
17. **Country with Overall Most Medals in Each Olympics** - Highlights the country with the highest total medals per edition.
18. **Countries That Never Won Gold** - Lists nations that have only won silver or bronze medals.
19. **India's Best Sport in Olympics** - Identifies the sport in which India has won the most medals.
20. **India's Hockey Olympic Medals** - Lists the Olympic editions where India won medals in hockey.

## How to Use
- Clone the repository:
  ```sh
  git clone https://github.com/MkPathan2113/olympics-sql-analysis.git
  ```
- Import the dataset into your SQL environment.
- Run the SQL queries to explore the data and extract insights.

## Requirements
- PostgreSQL (or any SQL-compatible database)
- SQL knowledge
- Dataset of Olympic history (OLYMPICS_HISTORY and OLYMPICS_HISTORY_NOC_REGIONS)


## Author
**Mokhit Khan**- Data Analyst / Data Scientist

## Contributing
Contributions are welcome! Feel free to submit a pull request with improvements or new queries.

## Contact
For any questions or discussions, feel free to reach out via GitHub Issues or email me at mokhitkhan@gmail.com

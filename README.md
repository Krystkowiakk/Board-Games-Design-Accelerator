# Board Games Design Accelerator
###### METIS Data Science and Machine Learning Bootcamp 2022 by Krystian Krystkowiak
###### project/month(3/7) focus: BUSINESS/EDA
#### Dashboard [Tableau](https://public.tableau.com/views/Metis-Project-3-Business-on-BGG/Dashboard4_1?:language=en-GB&:display_count=n&:origin=viz_share_link)
#### Presentation [GitHub](https://github.com/Krystkowiakk/Board-Games-Design-Accelerator/blob/f732eab3f9e0b51cd780f49bed0d67d01a78e181/Project%20Presentation/Krystkowiak_Krystian_Project_3_Business_on_BGG.pdf)

ABSTRACT

- Scraped BGG data for visualisation and analysis to identify the most in-demand features for board games, providing valuable insights for game designers and industry professionals.
- In this project, we used data analysis and visualization to uncover the secrets of the board game market and help game designers create winning games. By scraping and analyzing data from the ultimate resource for all things board games, Board Game Geek, and creating interactive visualizations with Google Sheets and Tableau, we were able to identify the most in-demand features and trends in the market. These insights will help game designers create bestselling games faster and with reduced financial risk.

DESIGN

The global board game market has experienced significant growth in recent years, particularly due to the impact of Covid-19 and related lockdowns. In 2021, the market was valued at USD 13.75 billion, and it is expected to reach a value of USD 30.93 billion by 2028.

In this project, I analyze data from the Board Game Geek (BGG) website to understand the factors that contribute to the success of highly-ranked board games. I identify the most in-demand mechanics and themes and explore how these features impact a game's rating and popularity. By understanding these trends, I aim to provide valuable insights for board game designers and publishers looking to streamline their design process and increase their chances of success in the market.

DATA

The data surce for this project is Board Game Geek (BGG) website, the most popular source of board game information on the internet (https://boardgamegeek.com/browse/boardgame).
I used scraped dataset from Kaggle: https://www.kaggle.com/datasets/jvanelteren/boardgamegeek-reviews?select=games_detailed_info.csv

The dataset includes information on 1822 board games, with 17 features for each game, including: name, BGG rating, themes, number of players, play time, complexity rating, and mechanic. The data has been filtered to include only games with at least 1000 rating votes and 100 complexity votes.

ALGORITHMS

- Data preprocessing: Filtering and cleaning data, converting categorical features to binary dummy variables
- Feature engineering: Creating new features (number of mechanics, words in the title, desired)
- Data visualization: Creating interactive bar plots of categories and mechanics based on BGG rating, creating Tableau visualizations

TOOLS

- Google Sheets: Used for exploratory data analysis and visualization

- Tableau: Used for creating interactive visualizations of the data

COMMUNICATION

In this project, I presented the findings through slides and visualizations created using Google Sheets and Tableau.

![Board Games Design Accelerator](files/cover.jpg)



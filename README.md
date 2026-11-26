# Analyzing Shifts in Popular Music Over Time


## Project Overview

This CS161 project seeks to analyze Billboard Top 100 data from two different datasets to discover trends in popular music over time. Within this project, we decided to look at musical topics and themes, artist demographics, usage of explicit language or topics, musical elements, and weeks charting at number one. 

### Technology
- This project was completed in python using a variety of libraries for data analysis, including: `numpy`, `pandas`, `matplotlib`, `sklearn`, `seaborn`.
- Additional details about library usage can be found in each Notebook.


## Questions of Interest

#### 1. What do topics in popular songs reveal about the social climate at the time?
- Contains analysis on: the 5 overall most popular lyrical topics, the most popular lyrical topics over each decade.
#### 2. Has the number of explicit songs increased over time? Have the reasons for being explicit changed?
- Contains analysis on: the amount of explicit songs, the reasons for being rated explicit.
#### 3. Is there a correlation between artist demographics and a song's top ranking?
- Contains analysis on: comparing the songs that reached #1 against the ones that never did for artist gender and race.
#### 4. How have musical elements of songs changed over time?
- Contains analysis on: musical keys, BPM, and instruments used on songs.


## File Organization

izzy_lyric_topic.ipynb
- Created by Izzy
- Tackling question #1

george_explicit.ipynb
- Created by George
- Tackling question #2

caden_artist_demographic.ipynb
- Created by Caden
- Tackling question #3

derecplots.ipnyb
- Created by Derec
- Tackling question #4

machinelearning.ipynb
- Created by Derec
- Tackling machine learning model

data/billboard.csv
data/top_100.csv
- CSV files containing all of our data, more documentation below

weeks_at-number_one_test_predictions.csv
- CSV file containing our machine learning model outputs

## Credits

### Contributors
- Caden Billy
- George Dokken
- Derec Gregory
- Izzy Robbins

### Final project for CS 161 with Professor Cheng at Willamette University

## Data

[Billboard Hot 100 Number Ones](https://github.com/rfordatascience/tidytuesday/blob/main/data/2025/2025-08-26/readme.md)
- Data on all songs ranked #1 from the Billboard Hot 100. Columns of interest: artist, producer, label, ranking, date, genre, instruments used, artist/producer demographic, explicit rating, etc.
- August 4, 1958 (first Billboard Hot 100) through January 11, 2025.
- Compiled by Chris Dalla Riva, sourced from TidyTuesday.

[Historic Billboard Hot 100 Data](https://github.com/mhollingshead/billboard-hot-100)
- Data on all songs from the Billboard Hot 100. Columns of interest: title, artist, ranking, previous ranking, best ranking, weeks on chart.
- August 4, 1958 (first Billboard Hot 100) through present.
- Compiled by Michael Hollingshead.


## Reflection

### Limitations
- There is very little public streaming data available because of privacy laws.
- We only have data for the United States because the Billboard Hot 100 is only a national ranking.
- There is only in-depth data for songs that reached #1 at some point.
- The demographic information on artists is very limited - we only have booleans for if the artist is male, white, or black.
- The Billboard Hot 100 started in August of 1958, so we have no earlier data on popular music.

### Future Goals
- We would love to explore how ratings change based on listener demographics. This could help provide insight on where to focus marketing for specific songs or artists.
- We would also be interested to see how these rankings change worldwide. It would be interesting to see how different places consume music, especially with how different cultures have different base scales or intruments their modern music is influenced by.
- Having the data from *Billboard Hot 100 Number Ones* for all 100 top songs would help our analysis determining what metrics exactly make a song reach/stay at #1. This could help record labels predict which songs or artists they should sign contracts with and help artists know what kind of songs would preform well.


## Important Links
[Project Proposal](https://docs.google.com/document/d/1CfKHIYFAo_kIuw2GRDKU1K3nqRkEbX4AUUhC-h3T8UA/edit?tab=t.0)

[Final Presentation](https://docs.google.com/presentation/d/1KoMceCInZA6d8JSCJ36G7yqRkAo15_hkZYadB5nSs3A/edit?usp=sharing)

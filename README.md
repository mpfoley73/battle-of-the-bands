# battle-of-the-bands
Using NLP to analyze song lyrics.

## What the project does

This project uses natural language processing to compare song lyrics from three icon bands with distinctive song-writing. On the one extreme, Rush's lyricist, Neil Peart, wrote some of the most erudite and textually challenging lyrics of any rock band. AC/DC, although not considered lyrically weak, is included as an unimpressive contrast to Peart. Queen is dark-horse in this analysis. All four members of Queen wrote songs individually, and as a group. Earlier songs, especially those written by Freddie Mercury, were extravagantly imaginative. How will Mercury's creativity show up in the analysis?

## Why the project is useful

This project is a fun analytic approach to exploring something that is easier to feel than to explain. AC/DC songs are easy to enjoy, but also easy to tire of. Queen and Rush are more difficult to acquire a taste for, but garner stronger feelings. This project is also a case study in the use of natural language processing (NLP) algorithms. The big two are present here: topic modeling, and sentiment analyis. I also performed complexity analysis and achieved interesting results.

## How users can get started with the project

Fork this project to start your battle of the bands, or clone and submit pull requests if you have any improvements.

## Where users can get help with your project

I narrated my analysis so that it functions somewhat as a tutorial. I also include links to the resources I used. Each section contributes insights that subsequent sections occasionally leverage. So if you are running the code, run each section in succession.

## Table of Contents

[Section 1](https://mpfoley73.github.io/battle-of-the-bands/1_get_lyrics.html) uses API and web scraping techniques to assemble a corpus of text for nearly 500 songs.

[Section 2](https://mpfoley73.github.io/battle-of-the-bands/2_exploration.html) is a brief overview of the corpus, including summary stats and trend charts.

[Section 3](https://mpfoley73.github.io/battle-of-the-bands/3_complexity.html) is the first NLP analysis. I measure text complexity using several measures. The **quanteda** package does almost all of the work, leaving the user with all of the fun.

Section 4 is a topic analysis. I have not started this yet.

Section 5 is a sentiment analysis. I have not started this either.

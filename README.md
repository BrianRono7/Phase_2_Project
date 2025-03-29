# Phase_2_Project

## MOVIE STUDIO BOX OFFICE ANALYSIS

## OVERVIEW

This project entails a series of data cleaning, imputation, analysis, and visualization with an aim of generating insights for our company as we embark on creating a new movie studio.


## BUSINESS UNDERSTANDING

The goal is to join the movie business through creation of films.The project therefore entails an analysis of the current films that are doing well at the box office with an aim of assisting the head of the company's new movie studio decide the type of films to create.

### Key business questions

1 Which are the most frequently watched films?

2 Which films have the highest gross returns?

3 What factors have an impact on the frequency of film watching and the gross returns?

## DATA UNDERSTANDING AND ANALYSIS
### Source of Data

The dataset has been scraped  from https://www.boxofficemojo.com/. It contains data from Domestic Box Office from 2024 to 2025.

### Description of Data

The main data points analyzed are;

- Movie
- Total Gross
- Opening weekend gross
- Opening weekend % of Total
- MPAA
- Running time
- Genres
  

Before data cleaning the dataset had 316 rows and 15 columns.On further exploration three columns were found to have missing values,i.e MPAA, Running time & opening weekend % of total.To cater for the missing values the MPAA missing points were replaced with Unknown values, while the other two had their missing values imputed by their median values.

## VISUALIZATIONS

1. Genre Distribution Analysis - The number of movies associated with the different genres.

![alt text](image.png)


2. Genre Perfomance Analysis - The average gross return per genre

![alt text](image-1.png)


3. Runtime Distribution

![alt text](image-2.png)


4. MPAA Rating Impact

![alt text](image-3.png)


## CONCLUSION

This analysis leads to the following insights and recommendations;


### Genre Strategy

Analysis of 2024-2025 Domestic Box Office shows Drama, Thriller, and Comedy dominate in movie count, while Musical, Family, and Sci Fi lead in Median Total Gross. Action Thriller hybrids are
common, suggesting blending genres boosts popularity. 

### MPAA Rating Considerations
PG and PG 13 films generate the highest earnings (PG avg. 81.57 M, PG-13 42.59M), making them ideal for broad audiences R rated films earn less (median 4.79 M), while G and Unknown ratings perform poorly. Focusing on PG/PG 13 maximizes reach and revenue.

### Runtime Optimization
Optimal movie runtime for engagement and box office success is 100-130 minutes, balancing storytelling and retention. Most films run 70-200 minutes; extremely short or long runtimes are less common and risk lower performance.


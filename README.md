# Phase_2_Project

## MOVIE STUDIO BOX OFFICE ANALYSIS

## OVERVIEW

This project entails a series of data cleaning, imputation, analysis, and visualization with an aim of generating insights for our company as we embark on creating a new movie studio.


## BUSINESS UNDERSTANDING

The goal is to join the movie business through creation of films.The project therefore entails an analysis of the current films that are doing well at the box office with an aim of assisting the head of the company's new movie studio decide the type of films to create.

### KEY BUSINESS QUESTIONS

1 Which are the most frequently watched genres?
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
- In release


Before data cleaning the dataset had 316 rows and 15 columns.On further exploration three columns were found to have missing values,i.e MPAA, Running time & opening weekend % of total.To cater for the missing values the MPAA missing points were replaced with Unknown values, while the other two were had their missing values imputed by the median.

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

The genre distribution analysis of Domestic Box Office rankings for 2024 and 2025 reveals that Drama, Thriller, and Comedy dominate in terms of movie count. However, when examining Median Total Gross (USD), the highest-earning genres were Musical, Family, and Sci-Fi, indicating that while some genres are more common, they do not necessarily generate the highest revenue. Additionally, an analysis of Genre Combinations highlights that Action and Thriller frequently appear together, suggesting that hybrid genres, particularly those blending action elements, remain popular. This insight can inform strategic decisions on film production and marketing to balance commercial success with audience preferences.


### MPAA Rating Considerations
The analysis of MPAA ratings indicates that PG and PG-13 rated movies tend to generate higher and more consistent gross earnings, making them ideal for targeting a broader audience. The data also reveals that these ratings exhibit more frequent outliers, suggesting variability in performance but also the potential for significant box office success. Specifically, PG-rated films have the highest average gross $81.57M, followed by PG-13 films $42.59M. In contrast, R-rated movies show lower earnings with a median gross of $4.79M, while G-rated and "Unknown" rated movies have the lowest financial performance. These findings highlight the strategic advantage of focusing on PG and PG-13 ratings to maximize both audience reach and box office returns.

### Runtime Optimization
The analysis of movie runtime suggests that the optimal duration for maximizing audience engagement and box office performance falls between 100 to 130 minutes. Films within this range are more likely to balance storytelling depth and viewer retention. Additionally, the distribution of movie runtimes indicates that the majority of films are between 70 and 200 minutes, with extreme runtimes (either too short or too long) being less common. To optimize viewership and financial success, it is advisable to avoid excessively short or long films, as they may not align with audience expectations or industry standards.


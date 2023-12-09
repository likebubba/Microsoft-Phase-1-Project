# Phase 1 Project Template - Minimum Viable Product (MVP)

![logo](images/director_shot.jpeg)

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### The Data

In the folder `Data` are movie datasets from:
* Bom movies
* IMDB database
* Movie Budgets
* TMDB database
* Tn movie budgets

## Overview 
In launching a studio we seek to maximize on profit for any new movie we produce.
That is to say, we are focussed on sales and net profit.
It is important to understand correlation between profitability and popularity and ratings.

## Business Understanding
We need to define optimal choices for the various inputs that we control as decision makers.
The inputs we do control -  Budget, Genre, Staffing, Scheduling, Run length, and more.

**Genre ratings**
![genre_ratings](images/genre_ratings.png?raw=true)

**Top grossing movies production budgets**
![production](images/production.png?raw=true)

**Top world wide grossing movies**
![grossing](images/worldwidegross.png?raw=true)



# Top Genres based on high Worldwide income gains
* Action
* Adventure
* Animation
* Sci-Fi

***
**Recommendation**
* Would recommend investing in Action, Adventure and Animation genres.This is based on profitability.

**Limitations**
* The analysis is limited to data provided.
* To improve on data analysis, need to source more data.

### top-level directory layout

    .
    ├── data               # provided input files for project
    ├── .gitignore
    ├── README.md
    ├── presentation.pdf        # project presentation PDF
    ├── student.ipynb           # analysis notebook
# YBI_Internship
# Movie Recommendation System (Machine Learning Project)

## Project Overview
This project implements a **Content-Based Movie Recommendation System** using Python and Machine Learning techniques.  
The system recommends movies by analyzing **text-based metadata** such as genre, keywords, tagline, cast, and director.

---

## Objective
- Understand content-based recommendation systems
- Apply text processing and similarity measures
- Perform feature engineering on real-world movie data
- Build a basic ML-powered recommendation engine

---

## Recommendation Approach

### Content-Based Filtering
- Recommends movies similar to a given movie
- Does not require user ratings or history
- Uses only movie metadata

Advantages:
- No cold-start user problem
- Explainable recommendations
- Suitable for small/medium datasets

---

## Dataset Information
- Total Movies: **4,760**
- Total Features: **21**

Important columns:
- Movie_Title
- Movie_Genre
- Movie_Keywords
- Movie_Tagline
- Movie_Cast
- Movie_Director
- Movie_Budget
- Movie_Revenue
- Movie_Runtime
- Movie_Vote
- Movie_Popularity

Dataset Source:  
https://github.com/YBIFoundation/Dataset

---

## ⚙️ Feature Selection
Selected text-based features:
- `Movie_Genre`
- `Movie_Keywords`
- `Movie_Tagline`
- `Movie_Cast`
- `Movie_Director`

Missing values handled using:
```python
.fillna('')

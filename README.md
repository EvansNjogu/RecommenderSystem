# Recommender System

This project implements a content-based movie recommender system using the k-Nearest Neighbors (kNN) algorithm. It features data preprocessing, sparse matrix construction, user bias analysis and movie similarity recommendations. The project also includes insightful visualizations to understand user preferences and movie ratings.


## **Example Outputs**
### **Recommendation Example**
If the input movie is *"Home Alone (1990)"*, the recommendations might include:
```
Since you watched 'Home Alone (1990)':
- Mrs. Doubtfire (1993)
- Lion King, The (1994)
- Pretty Woman (1990)
- Jurassic Park (1993)
- Jumanji (1995)
- Speed (1994)
- Forrest Gump (1994)
- Aladdin (1992)
- Mask, The (1994)
- Indiana Jones and the Temple of Doom (1984)
```

## **User Bias vs Ratings for a Selected Movie**


This visualization compares user ratings for a specific movie (e.g., *"Home Alone (1990)"*) with their calculated user bias (average rating behavior across other movies).

<img src="assets/uservsratings.png" alt="User Bias vs Ratings" width="800">

### **Key Insights:**
1. **Blue Dots (Ratings):**
   - Represent individual user ratings for the selected movie.
   - A scattered spread of ratings indicates varying opinions about the movie.

2. **Orange Line (User Bias):**
   - Represents each user's average rating behavior across all movies they have rated.
   - Acts as a benchmark to compare individual ratings for the selected movie.

3. **Green Dots (Above Bias):**
   - Highlight users whose ratings for the selected movie are higher than their average rating behavior (bias).
   - These users likely enjoyed the movie more than their typical preferences.

### **What It Tells Us:**
- **Above Bias:** Users with green dots may recommend the movie to others.
- **Below Bias:** Users with blue dots below the orange line rated the movie lower than their typical average, indicating it may not align with their general preferences.

This visualization provides actionable insights into user satisfaction and helps refine recommendations.


## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

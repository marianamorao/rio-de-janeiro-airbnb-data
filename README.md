# Airbnb Rio de Janeiro Data Analysis

## Project Overview
This project analyses Airbnb listings in Rio de Janeiro, Brazil, to uncover insights about popular neighbourhoods, pricing trends, and factors influencing guest satisfaction. The analysis focuses on the **Top 10/Top 20** listings, hosts, and neighbourhoods to provide actionable insights for hosts, travellers, and stakeholders.

## Key Questions Explored
1. **What are the Top 10 most popular neighbourhoods, and how do they compare in terms of prices and reviews?**
2. **What are the Top 10 most expensive neighbourhoods, and what room types are most common there?**
3. **What are the Top 20 listings with the highest review scores, and what features do they share?**
4. **What are the Top 10 most popular room types, and how do their prices and availability vary by season?**
5. **Who are the Top 10 hosts with the most listings, and how do their properties perform?**

## Libraries Used
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib** and **Seaborn**: For data visualisation.
- **Scikit-learn**: For additional analysis (if needed).

## Files in the Repository
- `setembro2019.csv`: The dataset containing Airbnb listings in Rio de Janeiro.
- `airbnb_rio_analysis.ipynb`: Jupyter Notebook with the complete analysis, visualisations, and insights.
- `README.md`: This file, providing an overview of the project.

## Results Summary
- **Most Popular Neighbourhood**: Copacabana has the highest number of listings (8,530), with an average price of R$498.17 and a review score of 93/100.
- **Most Expensive Neighbourhood**: Ramos tops the list, with an average price of R$3,472.33 per night.
- **Top-Rated Listings**: Listings with the highest review scores often offer entire homes/apartments and are managed by superhosts.
  - **Room Types**: 65% of the top-rated listings are entire homes/apartments.
  - **Superhosts**: 0% of the top-rated listings are managed by superhosts.
  - **Top 10 Amenities**:
     - **Kitchen**: 19 listings
     - **Wi-Fi**: 17 listings
     - **TV**: 16 listings
     - **Essentials**: 16 listings
     - **Laptop-friendly workspace**: 15 listings
     - **Air conditioning**: 13 listings
     - **Family/kid friendly**: 13 listings
     - **Elevator**: 12 listings
     - **Iron**: 9 listings
     - **Washer**: 9 listings

## How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/marianamorao/rio-de-janeiro-airbnb-data.git

## Medium blog post
https://medium.com/@marianamorao/exploring-airbnb-listings-in-rio-de-janeiro-what-makes-a-listing-successful-029f061ad91d

## Acknowledgments
The dataset used in this analysis was sourced from [Inside Airbnb](http://insideairbnb.com/) and is available on [Kaggle](https://www.kaggle.com/datasets/allanbruno/airbnb-rio-de-janeiro/data). Special thanks to Allan Bruno for making this dataset publicly available.

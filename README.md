# ZOMATO-API
## Case Study on Indian Startup : Zomato

**Zomato APIs** give you access to the freshest and most exhaustive information for over 1.5 million restaurants across 10,000 cities globally.
By Collecting the data using Zomato API one can recommend restaurants on the basis of user’s affinity to specific cuisines, establishment types, locations, and price bands.
We can find out whether restaurant support online reservation or not. We can find what is the most popular and/ or exclusive/new at a given location & time.

So I tried to answer some of the popular questions through my own Zomato API and they are:-

**1. As our dataset is highly skewed toward the cities included in Delhi-NCR. So, we will summarise all the other cities in Rest of India while those in New Delhi, Ghaziabad, Noida, Gurgaon, Faridabad to Delhi-NCR. Doing this would make our analysis turn toward Delhi-NCR v Rest of India.**
  - Plotting the bar graph of number of restaurants present in Delhi NCR vs Rest of India.
  - Finding the cuisines which are not present in restaurant of Delhi NCR but present in rest of India.Check using Zomato API whether this cuisines are actually not served in restaurants of Delhi-NCR or just it due to incomplete dataset.
  - Finding the top 10 cuisines served by maximum number of restaurants in Delhi NCR and rest of India.
  - Writing a short detailed analysis of how cuisine served is different from Delhi NCR to Rest of India. Plot the suitable graph to explain your inference.


**2. User Rating of a restaurant plays a crucial role in selecting a restaurant or ordering the food from the restaurant.**
  - Writing a short detail analysis of how the rating is affected by restaurant due following features: Plotting a suitable graph to explain my inference.
    - Number of Votes given Restaurant
    - Restaurant serving more number of cuisines.
    - Average Cost of Restaurant
    - Restaurant serving some specific cuisines.
  - Finding the weighted restaurant rating of each locality and finding out the top 10 localities with more weighted restaurant rating?
    - Weighted Restaurant Rating=Σ (number of votes * rating) / Σ (number of votes) .

**3. Visualization**
    - Plotting the bar graph top 15 restaurants have a maximum number of outlets.
    - Plotting the histogram of aggregate rating of restaurant( drop the unrated restaurant).
    - Plotting the bar graph top 10 restaurants in the data with the highest number of votes.
    - Plotting the pie graph of top 10 cuisines present in restaurants in the USA.
    - Plotting the bubble graph of a number of Restaurants present in the city of India and keeping the weighted restaurant rating of the city in a bubble.

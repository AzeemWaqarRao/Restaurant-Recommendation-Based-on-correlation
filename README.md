# Restaurant-Recommendation-Based-on-correlation

## Purpose:
This Notebook Recommends Restaurants based on correlation<br />

## Correlation:
Customer A likes restaurants 1 and 2. <br />
Customer B like restaurant 2 so he's most probable to like restaurant 1 too.<br />

## Data:
1-We have a ratings data which contains ratings given to different restaurants by different users.<br />
2-We have a cuisine data which contains cuisines of different restaurants.<br />
3-We have gio locations data which contains locations and names of restaurants.<br />

## Libraries Used:
1-Pandas<br />
2-Numpy<br />

## Approach
1-From the ratings data we group the data by restaurant's ID.<br />
2-Then we find the count of ratings for each restaurant and averge rating.<br />
3-Hence we will get a data frame with restaurants, their count of ratings and average rating.<br />
4-Merge this data frame with most rated restaurants.<br />
5-Now find a pivot table for each users rating of each restaurant.<br />
6-Find the most rated restaurant and find its correlation with other restaurants.<br />
7-Add the correlation with ratings data.<br />
Hence we can recommend a Restaurant based on high correlated with most rated restaurant and its cuisine.<br />

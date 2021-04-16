# The best place to live in San Francisco for a family with children

Thousands of people dream about moving to San Francisco. 
Of course, a life in a big city on the Pacific coast has many benefits. 
In fact, the list of reasons to live in San Francisco is rather extensive and many people from around the world move here.

What about moving to San Francisco with children? 
It is very important to find a place or neighborhood which will be comfortable for kids. 
With schools, parks, ice cream cafes and so on. Kids should love this place and be happy there.

**So, the question is how to find a great place to live in San Francisco with children?**


## Data
To find a solution for the question above here we’ll need the following data
- List of San Francisco neighborhoods: [SF zip codes and neighborhoods](http://www.healthysf.org/bdi/outcomes/zipmap.htm)
- **Google Geocoding** geo coordinates of neighborhoods
- **Foursquare** venues data for closest schools, parks, kids sores and other attractions
for each neighborhood: [foursquare](https://developer.foursquare.com/)


## Methodology
**K-Means clustering** algorithm is used to find out which areas(clusters) are more convenient for living with children.

Steps:
1. Find the best "K" value using **"elbow"** method.
2. Run K-Mean clustering algorithm using the best "K" value

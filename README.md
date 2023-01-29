# Foodstyles
This project aims to find answers for below question by a dataset containing information about restaurants all over Europe. 
The goal of the project is to make sense of the dataset and understand it in such a way that informed, data-based business decisions can be made. To make things easier, the project is split into three conceptually independent parts, with action points at each part. 
1.  Data cleaning
    a.Identify the columns with mixed data types.
    b.For each column, count the number of rows per data type.
    c.Would removing missing values solve the mixed data type problem?
2.  Data understanding
    a.Are the review columns correlated with the rating columns? 
      Review columns: ["excellent", "very_good", "average", "poor", "terrible", "total_reviews_count", "reviews_count_in_default_language"]
      Rating columns: ["food", "service", "value", "atmosphere", "avg_rating"]
    b.Are vegetarian-friendly restaurants better than non-vegetarian ones?
    c.Are there any significantly more expensive cuisines?
3.  Business-specific
    a.In the assets directory, you will see a very small dataset called europe_capitals_population_and_area.csv. A gluten-free restaurant wants to open a new restaurant in a European capital where gluten-free restaurants are underrepresented. Assuming there are no other factors, except population and gluten-free restaurant density, what would be the top 5 capitals to open that restaurant?
    b.Think and propose a couple of other ways this dataset could be used to help businesses.
4.  Bonus
    In the assets directory, you will see a file called paris_bounding_polygon.json. This contains a list of latitude and longitude coordinates that define a polygon that is considered to represent the Paris city area. For simplicity, we assume the population distribution is uniform in the Paris city area. An Italian restaurant wants to open a restaurant in Paris in a zone where there are the fewest Italian restaurants. What is the best location to open the restaurant (the answer can be a single point or a bounding box/polygonal region depending on the implementation)?

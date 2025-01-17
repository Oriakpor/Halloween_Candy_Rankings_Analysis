### Candy Analysis
## The candy analysis is a comprehensive Python-based analysis with visualizations that provides a detailed analysis of candies with the highest win, what they have in common, correlation between popularity and price/sugar contents of candies, etc. 

### Project objectives
The project aim to ascertain:
- Which candies have the highest win percentage? What do they have in common?
- Are more expensive candies more popular? What about sugary candies?
- Can you segment the candy into specific groups?
- If you had to pick 3 candies to give out in Halloween, which would they be?

### Data Source: The Halloween Candy Rankings data was obtained from Maven Analytics:
- [https://mavenanalytics.io/data-playground]

### Results
## 1a. Candies with the highest win percent are:
- Reese's Peanut Butter cup (84.18%)
- Reese's Miniatures (81.87%)
- Twix (81.64%)
- Kit Kat (76.77%)
- Snickers (76.67%)

## 1b. Common Features the candies have in common are:
- pluribus            (44)
- fruity              (38)
- chocolate           (37)
- bar                 (21)
- hard                (15)
- caramel             (14)
- peanutyalmondy      (14)
- nougat              (7)
- crispedricewafer    (7)

## 2. The correlation coefficient b/w Price Vs. Popularity, and Sugar and Popularity is: 0.345 and 0.229 respectively – indicating weak positive correlations. Thus, we cannot say the more Expensive/high Sugar content a candy has, the more popular they are. That is; price and sugar contents are not a dominant factor. However, the plotted scatterplot gave a clearer pic. From the scatter-plot, we observed the following:
- There are expensive candies that are not popular, and also expensive candies that are clustering above (very popular). This thus re-affirm the earlier correlation coefficient we earlier calculated (weak positive correlation). There's no clear trend or consistency, hence we conclude that price has some effect on popularity, though not dominant.
- There are also sugary candies that are quite popular, and not popular as well. There's no clear trend/consistent pattern on the scatterplot. This further re-affirms the correlation coefficient (very weak positive correlation) calculated. Hence, sugar contents do have a positive effect on the popularity of candies, though negligible.
- Lastly, between Sugar contents and Price, price has more effect on the popularity of candies.

## 3. Segmenting candies on the basis of Sugar, Price, Popularity and other diverse features. These are the top 5 candies:
- Sugar: 100 Grand (0.732%), 3 Musketeers (0.604%), One dime (0.011%), One quarter (0.011%), and Air Heads (0.906%)
- Price: 100 Grand ( 0.860%), 3 Musketeers (0.511%), One dime (0.116%), One quarter (0.511%), Air Heads (0.511%)
- Popularity: 100 Grand (66.97%), 3 Musketeers (67.60%), One dime (32.26%), One quarter (46.12%), and Air Heads (52.34%)

### If we are to pick 3 candies on the basis of popularity, price, and other diverse features - chocolate, fruity, bar, and pluribus. What we get is:
- Reese's Peanut Butter cup
- Twix          
- Reese's pieces

### Recommendations Based on Candy Analysis
## 1. Top Performing Candies
The candies with the highest win percentages—Reese's Peanut Butter Cup, Reese's Miniatures, Twix, Kit Kat, and Snickers—share common features such as being chocolate-based, containing caramel or peanut/almond elements, and having a bar or pluribus structure. These features strongly correlate with higher popularity and should be prioritized when designing or marketing new candies aimed at maximum consumer appeal.

## 2. Price and Sugar Impact on Popularity
Both price and sugar content exhibit weak positive correlations with candy popularity. Hence, the focus should be on creating candies that strike a balance between affordability and sweetness, while emphasizing other popular features like chocolate or caramel.

## 3. Feature-Based Segmentation
Segmentation analysis reveals clear patterns in consumer preferences:
- Sugar Segment: Candies like Air Heads and 3 Musketeers have higher sugar content but vary in popularity, indicating that other features influence consumer decisions beyond sweetness.
- Price Segment: High-priced candies such as 100 Grand are popular but not universally so, reiterating the need for diverse price points.
- Popularity Segment: Candies like Reese's Peanut Butter Cup and Twix are consistently high-performing across multiple metrics, showcasing the importance of leveraging features like chocolate and caramel.
- Conclusively, When introducing or optimizing candy products, target features such as chocolate, caramel, and pluribus design over simply increasing sugar content or raising prices.

## 4. When selecting candies that combine popularity, price, and desirable features such as chocolate, fruity, and bar attributes, the top choices are: 
- Reese's Peanut Butter Cup, Twix, and Reese's Pieces. Hence, focus marketing and production efforts on candies with these attributes as they demonstrate a winning combination of factors that resonate with consumers.





  




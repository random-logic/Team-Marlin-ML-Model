# Team-Marlin-ML-Model
## Problem we are trying to solve
Eating outside at restaurants is fun, especially as a night out with friends. However, this can be quite unhealthy, as we explore in the dataset. We aim to make an appliation that makes picking food from restaurants easy, while budgeting nutrient requirements and calories limits. Our goal is to recommend restaurant food to people by inputting their nutrient targets. How will we recommend these foods to people?

## Archive
- Our database: https://www.menustat.org/data.html
- Introduction / design choices: https://www.mdpi.com/2072-6643/14/7/1502
  - Conclusion: "The presence of unfamiliar ingredients and of animal-based ingredients may reduce the frequency with which specific dishes from a French restaurant menu are chosen, which may result in a reduced diversity in individuals’ diets." This shows that knowledge of ingredients can be important
  - "dining out was partially replaced by online food ordering from restaurants, which has also been linked with specific meal choice determinants"
    - Maybe we can add functionality to direct the user to a food ordering app like uber eats for better UI / UX design
  - type of restaurant impacts food choice = we should not drop this feature from our dataset
  - potential bias for findings: Polish caucasian women on French restaurants are only represented in the study
  - "food neophobia was associated with the reduced consumption or pleasure from the consumption of meat and offal" = potentially less protein?
  - high neophobia choose less soups = we can see if soups really do help with staying within nutrient budget
- https://www.mdpi.com/2072-6643/13/11/4132
  - 36.8% of expenditures for food outside (restaurant food) is fast food ... relatively calorie-dense and nutrient-poor, as it contains more saturated fat, sodium, and cholesterol but less dietary fiber = we might want to block the type of restaurant (fast food, healthy option, etc...)
- https://www.kaggle.com/code/midouazerty/restaurant-recommendation-system-using-ml
- ?? next = find out why we still need this for fast food, I think some people prefer fast food because convenience
- data modeling choices: https://journalofbigdata.springeropen.com/articles/10.1186/s40537-022-00592-5
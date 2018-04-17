# Make-Effective-Data-Visualization
visual encoding, design principles and effective communication
## Summary
In order to evaluate a baseball player, the batting average and home runs are two significant indexes. From this project, we can find BMI from weight and height each player and analysis the relation between BMI and two indexes by using visual encoding. Exclude the total relationship, the visualization figure can also animatedly express the relation for different handedness players. Check [here](http://bl.ocks.org/limumu008/e3dc55768ee8971f73b2de044b2c2f70).
## Design
There are five variables including height, weight, batting average, home run and handedness in the dataset. In the beginning, I was tring to combine some varibales in order to analysis this dataset. So BMI(Body Mass Index) jumpped into my head. I used R to investigate the dataset and created a new variable BMI. BMI is a measure of body fat based on height and weight that is also an index to evaluate athletes. A normal BMI is between 18.5 and 24.9. So I was showing the relation between BMI and batting average in different handedness in [first try](http://bl.ocks.org/limumu008/3f7ee0b7361940b813137b4d4718f4f1).
After I posted on forums, I got some positive feedbacks and improved my project. First, I deleted all 0 value of batting average due to avoiding the noise. And then created three figures, BMI and Home Run, BMI and batting average and Home Run and batting average ,respectively. In addition, I added three buttons for each figures. In order to show differences between different handedness, I lied three color buttons.
## Feedback
1. "It looks good. But I'm very interested in the dots in the bottom line. For that dots, the baiting averages are 0, right?
Is it necessary to show on your figure? Or you may need to delete that dots or wrangling your data?"

2. "Looks good, I just have a few notes.

-You may want to consider removing the data points along the x axis for all those with a 0 batting average since I’m guessing they correspond to data for pitchers who don’t go up to bat and therefore add extra noise to the plot.

-I like the mouseover tooltip to be able to interact with the plot to see the specific data point information.

-Since you point out that batting average and home runs are significant indexes, you may want to consider replacing BMI with Home Runs on the plot to show that relationship. It’s hard to tell what relationship exists between batting average and BMI, to me it looks like those with a BMI between 22-28 had a wider range of batting averages, while those at lower and higher BMIs had a higher range of batting averages

-I found it interesting that very few, if any, pitchers were ambidextrous, although I probably wouldn’t add this handedness encoding to the plot unless there’s a clear relationship. To me it looks like players of all BMIs and batting averages have the same distribution of left, right and ambidextrous handedness"

3. "Awesome! This time you did a realy good job. It's clear to conclude that the higher the number of batting average is, the more the number of home run is. By clicking the handedness button, I can see different results for each handedness player. And it looks no significant difference. Is it possible to show that? In a word, I like the figures you made." 

4. "I can now see a much clearer relationship between batting average and home runs, the higher the batting average the more home runs, which is what I would expect to see :+1:"
## Resources
1. http://dimplejs.org/advanced_examples_viewer.html?id=advanced_interactive_legends
2. http://bl.ocks.org/jone4291/raw/9714a9e3b7ee803e778a6a8d5ba1b168/
3. https://en.wikipedia.org/wiki/Body_mass_index

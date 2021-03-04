# End-to-end-Machine-learning-project


Welcome to Machine Learning Housing Corporation! Our project objective is build a model of housing prices in California using the California census
data. This data has metrics such as the population, median income, median housing
price, and so on for each block group in California. Block groups are the smallest
geographical unit for which the US Census Bureau publishes sample data (a block
group typically has a population of 600 to 3,000 people). We will just call them “districts”
for short.
Your model should learn from this data and be able to predict the median housing
price in any district, given all the other metrics.

### Working with Real Data
When you are learning about Machine Learning it is best to actually experiment with
real-world data, not just artificial datasets.

it is clearly a typical **supervised** learning project
since you are given labeled training examples (each instance comes with the expected
output, i.e., the district’s `median housing price`). Moreover, it is also a typical **regression**
task, since you are asked to predict a value. More specifically, this is a multiple
regression problem since the system will use multiple features to make a prediction (it
will use the district’s population, the median income, etc.). It is also a univariate
regression problem since we are only trying to predict a single value for each district.
If we were trying to predict multiple values per district, it would be a multivariate
regression problem. Finally, there is no continuous flow of data coming in the system,
there is no particular need to adjust to changing data rapidly, and the data is small
enough to fit in memory, so plain batch learning should do just fine.

In this project, we will go through an example project end to end, pretending to be a
recently hired data scientist in a real estate company. Here are the main steps you will
go through:
1. Look at the big picture.
2. Get the data.
3. Discover and visualize the data to gain insights.
4. Prepare the data for Machine Learning algorithms.
5. Select a model and train it.
6. Fine-tune your model.
7. Present your solution.
8. Launch, monitor, and maintain your system.



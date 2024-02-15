# App-user-segmentation
We need to group users based on how they engage with the app. Users who use an app daily and the users who have uninstalled the app engaged with the app. This data grouped together can help us find the retained and churn users.


Why we use it

App user segmentation is the task of grouping users based on how they engage with the app. It helps find retained users, find the user segment for a marketing campaign, and solve many other business problems where you need to search for users based on similar characteristics.

Step-by-step approach

Imported necessary Python libraries and Dataset
We can start by looking at the highest, lowest, and average screen time of all the users using min, max and mean
Now we take a look at the highest, lowest, and the average amount spent by all the users
Now let’s have a look at the relationship between the spending capacity and screen time of the active users and the users who have uninstalled the app
Now let’s have a look at the relationship between the ratings given by users and the average screen time
Analyzed all the above features using scatter plot
We use K-means clustering algorithm to find the users that the app retained and lost forever
Separated the segments and visualized them using plotly



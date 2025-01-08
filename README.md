# How Faithful is Old Faithful?

Old Faithful is a geyser in Yellowstone National Park that is famous for eruption on a fairly regular schedule. Run the cell below to see Old Faithful in action!

##### For the curious: this is a video displaying Old Faithful
##### https://www.youtube.com/watch?v=wE8NDuzt8eg

Some of Old Faithful's eruptions last longer than others. Whenever there is a long eruption, it is usually followed by an even longer wait before the next eruption. If you visit Yellowstone, you might want to predict when the next eruption will happen, so that you can see the rest of the park instead of waiting by the geyser.

Today, I will use a dataset on eruption durations and waiting times to see if we can make such predictions accurately with linear regression.

The original dataset has one row for each observed eruption. It includes the following columns:

duration: Eruption duration, in minutes

wait: Time between this eruption and the next, also in minutes


## Picture: 

In the picture below, I have added the predicted column after training data and predicted the wait time. 

It includes the follow columns: 

duration: Eruption duration, in minutes

wait: Time between this eruption and the next, also in minutes

predicted: Predicted time between this eruption and the next, in minutes

![Screenshot 2025-01-07 at 4 52 44 PM](https://github.com/user-attachments/assets/54338854-7549-46f3-a319-acf6a3882776)

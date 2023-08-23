# Door_dash_food_delivery_pred
This is a project regarding door dash food delivery time prediction.

Firstly here we got the data from stratastracth on which we have to build a predictive model to predict the delivery duration of food items.

Get the data
We need to import all the necessary libraries
Explore and clean the data
Feature selection
feature extraction
split the data and build a model on training data
test the model
deploy the model and communicate the results
We Have to Build a model to predict the total delivery duration in seconds for DoorDash, It is very important for DoorDash to get this right, as it has a big impact on consumer experience. In this project we will build a model to predict the estimated time taken for a delivery.

We have the historical data from DoorDash and following are the features of our dataset:

Start: the time consumer submits the order (created_at)
End: when the order will be delivered to the consumer (actual_delivery_time)

market_id: A city/region in which DoorDash operates, e.g., Los Angeles, given in the data as an id

created_at: Timestamp in UTC when the order was submitted by the consumer to DoorDash. (Note this timestamp is in UTC, but in case you need it, the actual timezone of the region was US/Pacific)

actual_delivery_time: Timestamp in UTC when the order was delivered to the consumer

store_id: an id representing the restaurant the order was submitted for

store_primary_category: cuisine category of the restaurant, e.g., italian, asian

order_protocol: a store can receive orders from DoorDash through many modes. This field represents an id denoting the protocol

total_items: total number of items in the order

subtotal: total value of the order submitted (in cents)

num_distinct_items: number of distinct items included in the order

min_item_price: price of the item with the least cost in the order (in cents)

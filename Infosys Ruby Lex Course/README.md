# Infosys Ruby Lex Course Exercises

1. Problem Statement:

Objective: Develop a Ruby program to store the train number, train name, and also the rating provided for the train with the total cost.

Problem Description: InfyRail is an online train inquiry application that is used to check for the details of trains on a particular route. Define four variables train_number, train_name, rating, and total_cost, and store different values for them. The value stored for train_number should be numeric, train_name should be string and rating should be a floating point number. Additionally, calculate the total_cost as below:

total_cost=base_fare-discount

The output should be structured as shown in the sample output.

Note: train_number cannot be changed.

2. Develop a Ruby program to enter the speed of the train and check if it is either express train , passenger train or a bullet train. 

For express trains, speed range => 45kmph - 75 kmph

For passenger trains , speed range => 30kmph- 45kmph

For bullet trains , take speed range => 75kmph - 90kmph.

3. Problem Statement:

Objective: Develop a Ruby program to store the traveler id, first name, last name, and phone number, in the form of an array and display the elements one by one with corresponding integer values using each loop.

Problem Description: Define a variable infy_rail and store different data such as traveler_id, first_name, last_name, and phone_number, in the form of an array. The value stored for traveler_id should be numeric, first_name and last_name should be string and phone_number should also be numeric. Display all the data along with the index number.

4.Problem Statement:

Objective: Develop a Ruby program to store traveler id, traveler name, and traveler destination values in different keys as symbols and display an appropriate message.

Problem Description: Define a variable infy_rail and store different values for traveler_id, traveler_name, and traveler_dest in the form of an key-value pair. The value stored for traveler_id, traveler_name and traveler_dest should be string and display an appropriate message.

5. Problem Statement:

Objective: Develop a Ruby program to collect train id,  traveler id, train name, traveler name, and phone number and print all the data one by one.

Problem Description: Collect data for train_id, traveler_id, train_name, traveler_name, and phone_number in the form of a collection. Then iterate through it and execute the data one by one.

6. Problem Statement:

Objective: Develop a Ruby program to define two methods to add traveler's details and to remove traveler's details and call the methods according to the user's choice.

Problem Description: Define two methods add_travelerDetails and remove_travelerDetails with parameters like traveler_id, traveler_name, and phone_number, and as a user, first add the traveler details and then remove the details. 

7. Create a class ‘Details’ in Ruby to enter the name , age and berth  preference of a user travelling by train and print the details. Create another class ‘Preference’ to add a functionality where the user gets the berth only if the the age of the user is above 50. Create a subclass ‘Confirmation’ for  class ‘Preference’ to display “Tickets confirmed” if the age and name  (The name of the user should have less than 20 and more that 4 characters) criteria is met else display “System error, try again” .

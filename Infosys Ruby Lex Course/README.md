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

8. Problem Statement:

Objective: Develop a Ruby program to check whether you are eligible for a discount that is given to senior citizens.

Problem Description: Define a class User which will have a method age_validation. In the method age_validation, take the age as input from the user and check whether the age is greater than 60 or not. If it is greater than 60, they can avail of a discount of 20%, and an appropriate message “Congratulations! You are eligible for a 20% of discount on your booking” should be displayed, if the age is >1 and <60 then display a message “Sorry! Only senior citizens are eligible for a discount.” else raise an  InfyRailException stating that “Invalid age ! Provide a valid age ”.

9. Problem Statement 

Background: This problem statement provides the high-level design of the project that has to be implemented as part of the hands-on assessment in order to complete the course Ruby Programming.

InfyGo is an airline application that provides airline services to its customers like search, book, cancel booked flights, etc which is going to be developed in Ruby. In this case study, you are required to design a few of the classes of the InfyGo application

Software Requirement:

Here is the software setup needed, before having a look at the requirements in detail.

Ruby à 3.1.2p20(x32 bit architecture)
VS Code à 1.66.2
Project Implementation:

Implement the below class diagram:

Flight Class:
Inside the class Flight, store all the datas such as flight_id(String datatype), airlines(String datatype), source(String datatype), destination(String datatype), fare(Float datatype), journey_date(String datatype) and seat_count(Integer datatype).
Flight_Service.Class:
flights:flights should be a hash variable where the keys is the flight_id and the value is Flight object.
Add Flight: Create a method add_flight  should add a Flight object into the hash variable .
Search Flight: Create a method search_flight. This will search the flight details based on the source, destination, and journey_date in flights(hash structure). If the provided journey date is during the festival season(Dec to Jan) then increase the flight fare by 20% for all search results before returning.
Raise an exception whenever the wrong flight details are given for search.

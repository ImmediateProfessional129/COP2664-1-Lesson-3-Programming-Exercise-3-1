# COP2664-1-Lesson-3-Programming-Exercise-3-1
This is a repository link of the COP2664-1 Lesson 3 Programming Exercise 3-1

// This program is designed to calculate the amount of money the driver has to pay for the traffic violation of going over the speed limit.

import Foundation // Imports the Foundation library 
var speedLimit = 50 // Sets the speed limit to 50
var drivingSpeed = 70 // Sets the driving speed to 70
if drivingSpeed <= speedLimit { // If the driving speed is less than or equal to the speed limit, then the program will print the following message.
  print("No ticket") // Prints the message "No ticket"
} else if drivingSpeed <= 20 { // If the driving speed is less than or equal to 20, then the program will print the following message.
  print("Ticket: $75") // Prints the message "Ticket: $75"
} else if drivingSpeed <= 40 { // If the driving speed is less than or equal to 40, then the program will print the following message.
  print("Ticket: $150") // Prints the message "Ticket: $150"
} else { // If the driving speed is greater than 40, then the program will print the following message.
  print("Ticket: $300") // Prints the message "Ticket: $300"
}
print("Infraction: Driving \(drivingSpeed) mph in a \(speedLimit) mph zone") // Prints the message "Infraction: Driving 70 mph in a 50 mph zone"

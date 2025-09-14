# ITT-assignment-2---Case-Study-2---Classroom-Monitor
Author: Cherise Kellman
Date: 13 September 2025
Student ID: u3167327
# Smart Classroom Monitor
This program simulates a Smart Classroom Monitor that allows the user to enter a topic, tracks student check-ins and check-outs, manages room capacity, monitors temperature, and controls the projector. It provides a simple interface for monitoring classroom data and generates a report which displays usage statistics.
# Features:
•	Topic manager: Set and update the current classroom topic
•	Student check-in/check-out: Track students entering and leaving the classroom
•	Capacity monitor: Caps room capacity at 25 students
•	Projector control: Toggle projector on or off and count activations
•	Temperature logging: Record and evaluate room temperature readings
•	Report generation: Display statistics including check-ins, check-outs, projector usage, topics and temperature data
# How this program works:
•	Topic manager: Allows the user to set and update the current classroom topic, displays previous topic.
•	Student check-in/check-out: Track students entering and leaving the classroom by asking student to input their name when checking in or checking out.
•	Capacity monitor: Enforces the maximum capacity of the classroom, does not allow students to check in if room is full.
•	Projector control: Allows the user to toggle projector on or off. Keeps track of how many times it was turned on or off
•	Temperature logging: Record room temperature readings and evaluates the minimum, maximum or average temperature.
•	Generates reports: Display statistics including check-ins, check-outs, projector usage statistics, topics and evaluates temperature data
# Instructions to user:
1.	Run the program in shell
2.	Follow the menu prompts to interact with the classroom monitor:
-	Press “t” to set a new topic
-	Press “i” to check-in a student
-	Press “o” to check-out a student
-	Press “L” to view list of checked-in students
-	Press “p” to toggle the projector on or off (menu will show projector status as True for on and False for off)
-	Press “r” to generate a report
-	Enter any number to log a temperature reading
# Requirements:
1.	Python 3 
2.	Console or terminal access
**No external libraires are required
# Troubleshooting
- If student already checked-in, duplicate names will receive message “student already checked-in”
- If room full, check-in is blocked when capacity is equal to 25
- Non-numeric value for temperature will receive an error message

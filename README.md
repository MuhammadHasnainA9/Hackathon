# Hackathon
solve some question using oop python for my first hackathon in saylani mass IT training
1. The "Smart" Quiz Engine (File I/O + Randomization)
•	The Task: Create a Quiz class. The program must read questions from a questions.txt file (Question | OptionA | OptionB | Answer). It should present 5 random questions to the user, track the score, and save the High Score to leaderboard.txt.
•	Parsing the text file correctly (splitting strings) and ensuring questions don't repeat during the session.

2. The Automated Parking Lot System
•	The Task: Create a ParkingLot class with a limited capacity (e.g., 5 slots). Vehicles are objects (Car, Bike).
o	Method park_vehicle(): Assigns the nearest empty slot.
o	Method remove_vehicle(): Calculates the fee based on hours parked ($2/hour).
o	Constraint: If the lot is full, it must raise a custom error/message.
•	Managing the "State" of the slots (which ID is taken vs. empty) using a Dictionary or List of Objects

3. The Movie Theater Seat Booker (Matrix Logic)
•	Real-Time Scenario: Booking specific seats in a cinema hall.
•	The Task:
o	Create a 5x5 Grid (List of Lists) representing seats. 0 = Empty, 1 = Booked.
o	Display the grid to the user.
o	The Trick: User inputs Row/Col (e.g., Row 2, Seat 3). Check if grid[2][3] == 0. If yes, change it to 1. If no, print "Seat Taken."
•	Logic Challenge: 2D Array manipulation and coordinate validation.

4. The "Food Panda" Order Queue Manager
•	Real-Time Scenario: Managing kitchen orders based on priority.
•	The Task:
o	Class Order: ID, Items, IsVIP (True/False).
o	Use a List as a Queue.
o	The Trick: When process_next_order() is called, it should normally take the first item. However, if a VIP order comes in, it must jump to the front of the line or be processed before standard orders.
•	Logic Challenge: Custom sorting or queue manipulation based on priority flags.

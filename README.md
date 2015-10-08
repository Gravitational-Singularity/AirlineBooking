# AirlineBooking

The program takes a manual user input and uses ArrayLists to store the data which the user gives it. The program then proceeds to recursively search for flights until the user chooses to terminate the program.

inputs must be done in the following fashion.
Example:

How many flights are there?
10

SOURCE DESTINATION AIRLINE FLIGHTID DATE
SFO SJC SOUTHWEST 1 03292015
SFO SJC LUFTHANSA 2 03292015
SJC JFK AIRCANADA 3 03302015
JFK SNA AIRFRANCE 4 04302015
JFK PIT UNITED 5 04302015
PIT JFK DELTA 6 04302015
SJC JFK DELTA 7 03302015
JFK PIT DELTA 8 04302015
SJC SFO SOUTHWEST 9 03292015
SFO SJC DELTA 10 03302015

Do you wish to book a flight? y/n
y
Okay.

Please enter your departure airport's code in capital letters
PIT

Please enter your destination airport's code in capitol letters
JFK
Routes Exists 

Please enter your departure date (mmddyyy)
04302015

Flights from JFK to PIT on 04302015 are:
Airline:DELTA   Flight ID:6   Number of remaining seats is 100 . 
 
 Please enter the flight ID of the flight you would like to book.
6

Please Enter how many tickets you would like to book.
50
Number of remaining seats is 50. 
Do you wish to book a flight? y/n
n
Okay. Goodbye.


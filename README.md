Formula 1 Championship & Performance Tracker - User Guide
Program by Ryan C



Welcome to the Formula 1 Championship & Performance Tracker! This program allows users to view key information about the 2024 Formula 1 season, including driver and constructor standings, race results, and driver/team performance. Follow the guide below to get started!


IMPORTANT - This program works with any csv under race results at: https://github.com/toUpperCase78/formula1-datasets/blob/master/Formula1_2024season_raceResults.csv. 

YOU WILL NEED TO REROUTE THE PATH OF THE CSV TO OPEN TO THE PATH TO YOUR CSV

Simply locate the csv file in your folder, right click and press copy as path, then paste it into main.py where file_path = (PATH).





1. Program Overview

The program allows you to:

- View the Driver's Championship Leaderboard.
- View the Constructor's Championship Leaderboard.
- View Race Results.
- Search for Driver Performance.
- Search for Team Performance.

It also allows you to:

- View driver performance graphs.
- See race-specific information.
- Get fastest lap information for each race.




2. Main Menu

When you run the program, you will be presented with the Main Menu, which looks like this:

------------------------------------------------------------
Welcome to the Formula One Championship and Performance Tracker!
------------------------------------------------------------
[1] View Driver's championship leaderboard
[2] View Constructor's championship leaderboard
[3] View race results
[4] Search for Driver performance
[5] Search for Team performance
[6] Exit
------------------------------------------------------------



3. Navigation

To navigate through the program, use the following instructions:

Step 1: Type a number between 1 and 6 to choose an option.
Step 2: Press Enter to confirm your selection.
Step 3: If needed, enter additional information (like a race name or driver's name) to get specific results.
Step 4: Follow any prompts to continue, view additional data, or return to the main menu.


4. Menu Options Explained



[1] View Driver's Championship Leaderboard

View the current standings of all drivers in the 2024 season.
The leaderboard shows each driver's position, team, and points.



[2] View Constructor's Championship Leaderboard

View the current standings of all teams in the 2024 season.
The leaderboard shows each team's position and points.


[3] View Race Results

Allows you to see results from any race.
Enter the name of a race (e.g., "Monaco, Australia") and view the race results, including each driver's position and points.
View the driver who set the fastest lap for that race.

Full list:
Bahrain
Saudi Arabia
Australia
Japan
China
Miami
Emilia Romagna
Monaco
Canada
Spain
Austria
Great Britain
Hungary
Belgium
Netherlands
Italy
Azerbaijan
Singapore
United States
Mexico
Brazil
Las Vegas
Qatar
Abu Dhabi

[4] Search for Driver Performance

Look up performance data for any driver.
Enter the driver's name (e.g., "Lewis Hamilton, Lando Norris") to view their performance in each race, total points, and championship rank.
View a graph of the driver's race results over the season.


Full list:
Charles Leclerc
Oscar Piastri
Lando Norris
Lewis Hamilton
Max Verstappen
Alexander Albon
George Russell
Nico Hulkenberg
Carlos Sainz
Fernando Alonso
Sergio Perez
Lance Stroll
Esteban Ocon
Pierre Gasly
Yuki Tsunoda
Guanyu Zhou
Liam Lawson
Jack Doohan
Oliver Bearman
Kevin Magnussen
Daniel Riccardo
Valtteri Bottas
Franco Colapinto



[5] Search for Team Performance

Look up performance data for any team.
Enter the team name (e.g., "Mercedes") to view the total points scored, wins, and drivers that have raced for that team.
View team performance over the season.

Full list:
Ferrari
Mercedes
Mclaren Mercedes
Red Bull Honda RBPT
Alpine Renault
Kick Sauber Ferrari
RB Honda RBPT
Aston Martin Aramco Mercedes
Haas Ferrari
Williams Mercedes



[6] Exit

Exit the program.



5. Key Features

Fastest Lap
In the Race Results section, you can see the driver who set the fastest lap in each race. This is indicated by the "🏎️ Fastest Lap" message.

Driver Performance Graph
After searching for a driver’s performance in Driver Performance, you have the option to view a graph of their performance in each race.
The graph shows the driver's finishing position in each race, with a lower position appearing higher on the graph.



6. Error Handling & Tips
Invalid Data: If the program encounters any invalid data (such as missing or incorrect race information), it will notify you and ask you to correct the input.
Spelling Issues: Be sure to enter the full name of the race or driver correctly. For example, if you type "McLaren," make sure it's spelled correctly, as it's case-sensitive.
Exit: If you ever wish to return to the main menu, you can simply type 'exit' or press Enter when prompted.


7. Example Walkthrough

Example 1: Viewing Driver Performance

Select option 4 (Search for Driver performance).
Enter the driver's full name (e.g., "Max Verstappen").
View the performance data, including:
Total points scored
Race results
Championship rank
You will then be prompted to view a graph of their performance across the races. Type 1 to view the graph or 2 to continue.
Example 2: Viewing Race Results

Select option 3 (View race results).
Enter the name of the race (e.g., "Bahrain Grand Prix").
The program will display the race results, including each driver's finishing position and points.
The fastest lap driver will also be shown if applicable.


8. Exiting the Program
To exit the program, simply select Option 6 from the main menu. This will close the program and terminate the session.


9. Troubleshooting
Problem: I entered a race or driver's name, but no results were found.
Solution: Double-check the spelling of the name, and ensure you're entering the full name (e.g., "Grand Prix" or full driver names like "Lando Norris").
Problem: The graph isn’t showing properly.
Solution: Ensure that the required libraries (e.g., matplotlib) are installed in your Python environment.

TennisDatabase was written by Dylan Lozon
for assignment 2 of CS-102

------ Program Info ------
This is a database that is
intended to store tennis 
players and their matches.
All data is input from and
output to text files. These
text files are not case-sensitive.

------- Input Info -------
When you start the program,
it will ask you for an input
file. Should you choose to
provide one, it will need a
particular format:

Each line should start with
either "Match" or "Player" to
signal the program which is coming.
All players should be listed
before any matches. All data
must be separated by '/'

Players have an ID, first name,
last name, birth year, and 
country of origin.

Ex. PLAYER/DJO87/NOVAK/DJOKOVIC/1987/SERBIA
EX. PLAYER/NAD86/RAFAEL/NADAL/1986/SPAIN

Matches have 2 players, 
represented by their respective
IDs, the date of the match, 
tournament, and score.

Ex. MATCH/DJO87/NAD86/20150316/INDIAN WELLS/6-3,6-7,6-2

An input file has been
provided for example.

------- Output Info -------
All output will be stored in 
the same format as the expected
input. This means that you will
be able to later use it as an
input, and load any changes 
you've made.
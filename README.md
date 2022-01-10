# plurality

This program simulates a plurality vote election with a maximum of 9 candidates.


To run this program, execute according to the examples below

$ ./plurality Anna Bruce <br />
Number of voters: 3<br />
Vote: Bruce<br />
Vote: Daniel<br />
Invalid Vote.<br />
Vote: Anna<br />
Vote: Bruce<br />
Bruce<br />

The program will declare Bruce as the winner of this plurality election.

$ ./plurality Anna Bruce Daniel<br />
Number of voters: 5<br />
Vote: Anna<br />
Vote: Bruce<br />
Vote: Anna<br />
Vote: Anna<br />
Vote: Daniel<br />
Anna<br />

Anna is the winner of this plurality election.

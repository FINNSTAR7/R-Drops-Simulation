# R-Drops-Simulation
This project was started to verify the expected and nearly guaranteed number of runs a Warframe player needs to collect all of a Warframe's components at least one time each.

simul.txt will count the number of trials it takes to succeed on each probability inputted for each sample. For example, inputting "`1/3, 1/3, 1/3`" into the "probs" line will have simul.txt count the number of trials until an individual sample succeeds on the first 1/3, the second 1/3, and third 1/3 probability at least once each. Once all probabilities have succeeded it will move on to the next sample, until the data for all 1,000,000 samples have been collected.

It will then calculate the average and plot the data.


Examples of Script Usage:<br />
`probs = c(0.5, 0.5);` (coin flip)<br />
`probs = c(1/6, 1/6, 1/6, 1/6, 1/6, 1/6);` (d6 toss)<br />
`probs = c(.75);`<br />
`probs = c(10, 20, 30, 40);`


To alter the number of samples desired (default is 1,000,000) edit the "`samples`" line (3rd line) in the simul.txt script itself.

For any questions or additional assistance please contact me through the wiki here: https://warframe.fandom.com/wiki/Message_Wall:FINNER

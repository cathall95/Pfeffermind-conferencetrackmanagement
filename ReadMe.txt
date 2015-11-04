This program is written using java. The ui is done with a Jframe.
It just requires the file ConferenceTrackManagement.java and the input file to run.

The input file is specified in the computeResult() method which is the first method under main. 
It is at the start of that method on this line: inputText = readFile("testinput.txt");

It is compiled at the command prompt with javac ConferenceTrackManagement.java .
It is executed at the command prompt with java ConferenceTrackManagement .

The program works by reading in the file and storing it as a string. It then seperates this string into a string array where each line of the file has its own index.
It then seperates the title and time of each line into two arrays. It then sorts these arrays using bubblesort based on the time from shortest to longest. 
It then fills the morning and evening sessions for each track. As it fills each session it displays the result to a text area contained in the jframe. It also removes the scheduled elements as it goes.
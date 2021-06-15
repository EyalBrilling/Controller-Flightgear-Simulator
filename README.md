Our program connects to "flightgear simulator" by Microsoft and serve as a server
which sends commands, and at the same time, also serve as a customer receiving commmands from flightgear to fly the plane.
The program will receive a text file and the desired commands for the flight. 

The program is built as a part of a programming course at Bar-Ilan University by Eyal and Sahar.


How it will work?
Here are the steps:

1. Download and install flight-gear : https://www.flightgear.org/download/
2. Enter to the "flightgear simulator" settings the following commands:

  --telnet=socket,in,10,127.0.0.1,5400,tcp --http=8080    
  
  --generic=socket,out,10,127.0.0.1,5402,tcp,generic_small
  
3. Plant the file 'generic_small.xml' in flightgear/Protocol
4. start the program with fly.txt
5. Open flightgear and click Fly.


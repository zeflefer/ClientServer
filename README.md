# ClientServer
Distributed Systems Simulation Project

This project is a Java simulation of a distributed system with:
Naming services: Flat, Hierarchical (Sequential), and Attribute-based

Processes and resources: Server and three clients with CPU/network resources
Consistency models: Strict and Eventual (with timestamps and gossip)
Client–Server architecture: Three clients send requests to a server

Requirements
Java 11 or later

HOW TO USE:
1. Unzip the zip file, then run the file on any Java compatible IDEs (Recommended: Netbeans)

2. When you run the program, you will be ask to:

Choose a naming service:
-Enter 1 for Flat
-Enter 2 for Sequential 
-Enter 3 for Attribute-based

3. Then the process will run, by doing naming lookup and takes requests from clients

4. Then you will be asked to choose a consistency model
-Enter 1 for Strict
-Enter 2 for Eventual
-Invalid inputs will print Invalid input, try again. until a valid choice is made.

5. Output Explanation
Naming demo: Shows lookup/query latency for the chosen naming service.
Server logs: Show when requests are processed and their processing latency.
Client logs: Show turnaround time (send → response) for each request.

Consistency demo:
-Write latency: Time to perform a put
-Read latency: Time to perform a get
-Eventual consistency: Convergence time until all replicas agree

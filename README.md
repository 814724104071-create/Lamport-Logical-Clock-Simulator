# Lamport Logical Clock Simulator

## CS3551 – Distributed Computing Mini Project

### 1. Project Description
This project simulates Lamport Logical Clocks in a distributed system. It demonstrates how logical clock values are updated for internal events, message sending, and message receiving across three processes (P1, P2, and P3).

### 2. Objectives
- To understand logical clocks in distributed computing.
- To simulate communication between distributed processes.
- To show the ordering of events using logical timestamps.
- To understand how message timestamps maintain causal ordering.

### 3. Technologies Used
- HTML
- CSS
- JavaScript

### 4. How to Run
1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Select a process and event type.
5. For sending or receiving, select the other process.
6. Click **Add Event** to view the updated logical clock and event log.
7. Click **Reset** to restart the simulation.

### 5. Lamport Clock Rule
- For an internal or send event: `C = C + 1`
- For a receive event with timestamp `T`: `C = max(C, T) + 1`

### 6. Sample Execution
1. Select P1 and choose **Internal Event**. P1 clock becomes 1.
2. Select P1 and choose **Send Message** to P2. P1 clock becomes 2.
3. Select P2 and choose **Receive Message** from P1. P2 clock becomes 3.

### 7. Result
The simulator successfully demonstrates Lamport logical clock updates and event ordering among three distributed processes.

## Author
Student Name: __________________  
Register Number: _______________  
Course: CS3551 – Distributed Computing

The Bank Queue (Poisson) Simulator

The Bank Queue (Poisson) Simulator is a C-based simulation that models customer arrivals and service at a bank over an 8-hour day (480 minutes).

The program uses the Poisson distribution to realistically simulate random customer arrivals and a linked list queue to manage waiting customers. It tracks each customer’s waiting time, computes statistical measures (like average and maximum wait times), and helps bank management analyze teller efficiency and customer service performance.

This simulation assists in data-driven decision-making about whether the bank should hire additional tellers to reduce waiting times.


---
 Concepts Used
 C Programming Concepts

for loops and if-else statements

struct for creating customer data structures

malloc() and free() for dynamic memory allocation

Linked lists to implement the customer queue

Functions for modular code design

rand() and srand() for generating random events

time() for random seed initialization

Input/output handling and data reporting


🔹 Mathematical Concepts

Poisson Distribution to model random arrivals

Mean (Average) and Maximum wait time calculations

Probability and random variation for service durations

(Optional extensions: Median, Mode, Standard Deviation)



---

⚙ How to Compile

Use the GCC compiler in your terminal or command prompt.

gcc bank_queue.c -o bank_queue -lm

Explanation:

bank_queue.c → your C source file

-o bank_queue → creates an executable named bank_queue

-lm → links the math library (for exp() and pow() used in Poisson calculations)



---

▶ How to Run

After compiling successfully, run the program with:

./bank_queue

💬 Example Run

Enter average number of customers arriving per minute (lambda): 0.5

===== Simulation Report =====
Total customers arrived: 245
Total customers served: 240
Average wait time: 2.37 minutes
Maximum wait time: 8 minutes
Customers still in queue: 5


---
Program Summary

Simulates 480 minutes (8 hours) of bank operations

Uses Poisson-distributed arrivals for realism

Each teller serves customers for 2–3 minutes

Tracks every customer’s arrival time, service time, and wait time

Outputs average and maximum wait times

Demonstrates use of pointers, linked lists, and probability in a practical application



---

Future Enhancements

Support for multiple tellers

Calculate median, mode, and standard deviation of wait times

Export results to a .csv file for data visualization

Add graphical output (using Python or Excel) for comparison of teller efficiency



---

✅ Author: Your Name
✅ Language: C
✅ Topic: Queue Simulation using Probability and Data Analysis


---

Would you like me to also generate a README with Markdown styling (bold titles, emojis, code blocks, bullets) ready to copy-paste into GitHub with perfect formatting (like professional repos)?

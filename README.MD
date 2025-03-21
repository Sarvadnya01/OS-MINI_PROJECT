🎮 OS Mini Project: Process Scheduling Algorithm Simulator
Welcome to your interactive playground for exploring process scheduling algorithms! Whether you're a student learning OS concepts or a curious coder, this GUI tool makes understanding scheduling algorithms visual, intuitive, and even fun!

🌟 Features
Simulate 5 Popular Algorithms: FCFS, SJF, SRTN, Priority, and Round Robin.

User-Friendly GUI: No command-line hassle—input values and visualize results in seconds!

Instant Metrics: See turnaround time, waiting time, and averages for all processes.

Perfect for Learning: Great for assignments, labs, or just satisfying your OS curiosity.

🚀 Quick Start
Prerequisites
Python 3.x (Download here)

Tkinter (usually pre-installed with Python. If missing, install with sudo apt-get install python3-tk on Linux).

Installation
Clone the Repository:

bash
Copy
git clone https://github.com/Sarvadnya01/OS-MINI_PROJECT.git  
cd OS-MINI_PROJECT  
Run the Simulator:

bash
Copy
python OS-Mini-Project-Scheduling-Algorithm.py  
(Wait for the GUI window to pop up—let the fun begin!)

🖥️ How to Use the Simulator
Step 1: Choose Your Algorithm
Pick from the dropdown menu:

FCFS (First-Come, First-Served)

SJF (Shortest Job First)

SRTN (Shortest Remaining Time Next)

Priority Scheduling

Round Robin (with customizable quantum time!)

Step 2: Enter Process Details
Number of Processes: Type a number (e.g., 3).

For Each Process:

Arrival Time: When the process arrives (e.g., 0, 2, 4).

Burst Time: How long the process needs the CPU (e.g., 5, 3, 7).

Priority (for Priority Scheduling): Lower number = higher priority.

Step 3: Hit "Submit"!
Watch the tool calculate:
✅ Completion Time
✅ Turnaround Time
✅ Waiting Time
✅ Average Turnaround & Waiting Times (Perfect for your lab reports!)

🧠 Algorithms Explained
Algorithm	Description
FCFS	Runs processes in the order they arrive. Simple but can cause long waits!
SJF	Picks the shortest job first. Minimizes waiting time but needs future knowledge.
SRTN	Preemptive SJF—interrupts running processes if a shorter job arrives.
Priority	Executes higher-priority processes first. Watch out for starvation!
Round Robin	Cycles processes with a fixed time slice (quantum). Fair but may be slower.
🤝 Contributions
- SARVADNYA KAKAD
- AYUSH GAMBHIRE
- PRACHEE WAKODE

🎉 Special Thanks
A big shoutout to the OS community for inspiring this project!

Happy Scheduling! 🌈
Let’s make operating systems a little less mysterious and a lot more magical.
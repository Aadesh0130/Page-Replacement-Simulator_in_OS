⚡ Page Replacement Algorithm Simulator
📌 Overview

The Page Replacement Algorithm Simulator is an interactive, browser-based tool designed to visualize and compare core memory management strategies used in Operating Systems.

It enables users to simulate how different page replacement algorithms behave under identical conditions, offering step-by-step execution, real-time visualization, and performance comparison.

🔗 Repository

GitHub Repository:
👉 https://github.com/Aadesh0130/Page-Replacement-Simulator_in_OS

Author:
👤 Aadesh0130

🚀 Features
🔄 Multiple Algorithm Support
FIFO (First-In First-Out)
LRU (Least Recently Used)
LFU (Least Frequently Used)
OPT (Optimal Page Replacement)
📊 Real-Time Simulation
Step-by-step execution
Auto-play mode with adjustable speed
Frame-by-frame visualization
📈 Performance Metrics
Page Fault Count
Hit Ratio
Fault Rate
Algorithm comparison chart
🧠 Interactive Learning
Visual indication of Hits & Misses
Evicted page tracking
Sequence progress tracking
🎲 Random Input Generator
Generate random page reference strings for testing
🏗️ Tech Stack
Frontend: HTML5, CSS3
Logic Layer: Vanilla JavaScript
Visualization: Canvas API
Styling: Custom modern UI (responsive + animated)
📂 Project Structure
📁 Page-Replacement-Simulator_in_OS
 ├── Page Simulator.html
 └── README.md
⚙️ How It Works

The simulator takes:

A page reference string
A fixed number of frames

Each selected algorithm processes the same input and:

Identifies HIT or MISS
Updates frames dynamically
Tracks performance metrics
Logs each step for analysis
🧮 Algorithms Explained
🔹 FIFO (First-In First-Out)
Removes the oldest page from memory.

Working Logic:

If page exists → HIT
Else → MISS
If frames full → remove first inserted page
Insert new page

Key Insight:
Can suffer from Belady’s Anomaly

🔹 LRU (Least Recently Used)
Removes the page least recently accessed

Working Logic:

Track last usage index
Replace page with oldest usage

Strength:
Efficient due to temporal locality

🔹 LFU (Least Frequently Used)
Removes page with lowest access frequency

Working Logic:

Maintain frequency count
On tie → apply LRU
Replace least used page
🔹 OPT (Optimal Algorithm)
Removes page that will be used farthest in the future

Working Logic:

Look ahead in reference string
Replace page with maximum future distance

Note:
Used as theoretical benchmark

📊 Performance Metrics
Page Faults → Total misses
Page Hits → Successful accesses
Hit Ratio → Hits / Total Requests
Fault Rate → Faults / Total Requests
🎮 Usage Instructions

Clone the repository:

git clone https://github.com/Aadesh0130/Page-Replacement-Simulator_in_OS.git

Open:

Page Simulator.html
Provide:
Page reference string
Number of frames
Run simulation:
▶ Run All
⏭ Step Execution
⚙ Auto-Play
📷 Interface Highlights
Real-time frame visualization
Step-by-step logs
Interactive page sequence tracker
Algorithm comparison chart
Best algorithm identification
🧠 Key Concepts Demonstrated
Demand Paging
Page Replacement Strategies
Locality of Reference
Memory Optimization
🏆 Best Algorithm Detection

The system automatically identifies the best algorithm based on:

Minimum page faults
Maximum hit ratio
📌 Example Input
Reference String: 7 0 1 2 0 3 0 4
Frames: 3
🔮 Future Enhancements
Clock (Second Chance) Algorithm
MRU Algorithm
Export results as PDF/CSV
Backend-based large-scale simulations
Deployment with live hosting
📜 License

This project is intended for educational use and is open for learning and enhancement.

👨‍💻 Author

Aadesh0130
GitHub: https://github.com/Aadesh0130

Demo Images of working


<img width="918" height="582" alt="image" src="https://github.com/user-attachments/assets/7e39c3e9-0796-4376-9fb9-1af4878d46e6" />


<img width="1047" height="598" alt="image" src="https://github.com/user-attachments/assets/debe9c4e-fc76-47c8-b85e-64be10c39982" />

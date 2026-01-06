🧠 Cache Mapping Policy Simulator

A Python-based mini project that simulates and compares different cache mapping techniques used in computer architecture.
This project evaluates cache performance using hit rate and miss rate analysis and visualizes the results.

📌 Project Overview

Cache memory plays a vital role in improving system performance by reducing memory access time.
This simulator compares the following cache mapping policies:

Direct Mapped Cache

Set Associative Cache (2-Way & 4-Way)

Fully Associative Cache

The simulator processes a generated memory access trace and analyzes cache behavior using different replacement strategies.

⚙️ Features

Configurable cache size and block size

Supports multiple cache mapping techniques

Implements replacement policies:

FIFO

LRU

Random

Calculates:

Cache Hits

Cache Misses

Hit Rate

Miss Rate

Displays results in tabular format

Visualizes hit rate comparison using bar charts

🛠️ Technologies Used

Python 3

pandas – data analysis

matplotlib – visualization

collections – cache structures

random – trace generation

📁 Project Structure
Cache-Mapping-Policy-Simulator/
│
├── cache_simulator.py    # Main source code
├── README.md             # Project documentation
└── requirements.txt      # Dependencies (optional)

▶️ How to Run the Project
1️⃣ Install Dependencies
pip install pandas matplotlib

2️⃣ Run the Simulator
python cache_simulator.py

📊 Sample Output
Console Output (Table)
Mapping	Hits	Misses	Hit Rate
Direct	120	180	0.40
2-Way	165	135	0.55
4-Way	190	110	0.63
Fully-Assoc	210	90	0.70
Visualization

Bar chart comparing hit rates of different cache mapping policies

🧪 Memory Trace Generation

The simulator generates a synthetic memory access trace that includes:

Locality of reference

Random memory accesses
This helps simulate realistic program behavior.

🎯 Learning Outcomes

Understand cache memory organization

Compare cache mapping techniques

Analyze cache performance metrics

Visualize architectural trade-offs

📚 Applications

Computer Architecture education

Operating Systems concepts

Cache performance analysis

Academic mini projects

👤 Author

Menagai Sriram
Mini Project – Cache Mapping Policy Simulator

📜 License

This project is intended for educational and academic use only.

# 🚉 Bhopal Metro Shortest Path Finder

This is a simple C++ project I built to find the shortest path between metro/bus stations in Bhopal. It uses **Dijkstra’s algorithm** to calculate how many stations you’ll pass through from one location to every other.

Basically, you choose a starting station, and it tells you how many stops it takes to get to all the others.

---

## 💡 What It Does

- Takes a list of 53 real metro/bus stations from Bhopal
- Treats them as connected points in a graph
- Uses **Dijkstra's algorithm** to find the shortest path (i.e., least number of stations)
- Outputs the shortest path from the source station to all other stations

---

## 🛠️ Tech Used

- **C++** – for logic and performance  
- **Graph Theory** – to model stations  
- **Dijkstra’s Algorithm** – to find the shortest route  

---

## 🚀 How to Run It

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/bhopal-metro-shortestpath.git
   cd bhopal-metro-shortestpath

Sample Output:

Enter source station:
Enter 0 for Gandhi Nagar
Enter 1 for Karond
...
Minimum stations from MP Nagar to AIIMS: 3
Minimum stations from MP Nagar to Bairagarh: 20

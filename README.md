# Vityarthi_project-25bai10120-CSA-
# ALGORITHM ANALYSER 
This program is used to suggest the least cost providing algorithm. It takes in a graph/ tree as input and analyses it based on algorithms (BFS, DFS, Hill Climbing, A*, Best First Search) and gives out the cost of each and the least cost algorithm. 

# Features

    Supports multiple search algorithms:

        * Breadth First Search (BFS)
        * Depth First Search (DFS)
        * A* Algorithm
        * Best First Search (Greedy)
        * Hill Climbing

    Compares:

        * Path found by each algorithm
        * Total cost of the path
        * Efficiency of traversal
        * Identifies the **best algorithm** based on minimum cost


# Algorithms Overview



## 📌 Input Format

Users can define the graph using edge lists:

Example:
A B 1
A C 3
B D 2
C D 1
D E 5

Heuristic values:
A: 7
B: 6
C: 2
D: 1
E: 0

Start Node: A
Goal Node: E

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/search-algorithm-analyzer.git
cd search-algorithm-analyzer
```

2. Install dependencies (if any):

```bash
pip install -r requirements.txt
```

3. Run the project:

```bash
python main.py
```

---

## 📊 Sample Output

BFS: Path = ['A', 'B', 'D', 'E'], Cost = 8
DFS: Path = ['A', 'C', 'D', 'E'], Cost = 9
A*: Path = ['A', 'C', 'D', 'E'], Cost = 7
Best First: Path = ['A', 'C', 'D', 'E'], Cost = 7
Hill Climbing: Path = ['A', 'C', 'D', 'E'], Cost = 7

🏆 Best Algorithm: A* (Minimum Cost = 7)

---

## 🛠️ Project Structure

search-algorithm-analyzer/
│
├── algorithms/
│   ├── bfs.py
│   ├── dfs.py
│   ├── astar.py
│   ├── best_first.py
│   ├── hill_climbing.py
│
├── utils/
│   ├── graph_input.py
│   ├── heuristics.py
│
├── main.py
├── config.py
├── requirements.txt
├── README.md

---

## 🌟 Future Enhancements

* Graph visualization using NetworkX
* GUI interface (Tkinter / Streamlit)
* Step-by-step algorithm animation
* AO* algorithm support (AND-OR graphs)
* Performance metrics (time, nodes explored)

---

## 👩‍💻 Author

Vaishnavi Yadav

---

## 📜 License

This project is open-source and available for learning and educational purposes.


# Social Network Degrees of Separation (BFS)
---
# Overview

This project implements a Social Network Degrees of Separation system using Python and the Breadth-First Search (BFS) algorithm.

The application models a social network as an undirected graph where each user represents a node and each friendship represents an edge. Friendship data is loaded from a CSV file, allowing the program to analyze user connections efficiently.

The system finds the shortest friendship chain between two users, calculates the degree of separation, identifies mutual friends, ranks the top five most connected users, and provides an interactive graphical visualization of the network.

---

# Features

* Load friendship data from a CSV file.
* Build a social network graph.
* Find the shortest path using Breadth-First Search (BFS).
* Calculate the Degree of Separation.
* Display mutual friends between two users.
* Identify the Top 5 most connected users.
* Interactive GUI built with Tkinter.
* Graph visualization using NetworkX and Matplotlib.
* Handle cases where no connection exists.

---

# Algorithm

The project uses the Breadth-First Search (BFS) algorithm to traverse the graph and find the shortest path between two users.

BFS explores nodes level by level, guaranteeing the shortest path in an unweighted graph, making it ideal for social network analysis.

## Time Complexity

| Operation             | Complexity |
| --------------------- | ---------- |
| Load Graph            | O(E)       |
| BFS Shortest Path     | O(V + E)   |
| Mutual Friends        | O(n)       |
| Top 5 Connected Users | O(V log V) |

Where:

* **V** = Number of Users
* **E** = Number of Friendships

---

# Screenshots

## GUI

```
screenshots/gui.png
```

## Shortest Path

```
screenshots/shortest_path.png
```

## Output

```
screenshots/output.png
```

After uploading the images to the `screenshots` folder, replace the code blocks above with:

```markdown
![GUI](screenshots/gui.png)

![Shortest Path](screenshots/shortest_path.png)

![Output](screenshots/output.png)
```

---

# Project Structure

```text
Social-Network-Degrees-of-Separation-BFS/
│
├── final project.ipynb
├── users.csv
├── README.md
└── screenshots/
    ├── gui.png
    ├── shortest_path.png
    └── output.png
```

---

# How to Run

1. Clone the repository.

```bash
git clone https://github.com/YOUR_USERNAME/Social-Network-Degrees-of-Separation-BFS.git
```

2. Install the required libraries.

```bash
pip install networkx matplotlib pandas
```

3. Open the project notebook.

```text
final project.ipynb
```

4. Run all notebook cells.

5. Load the `users.csv` dataset.

6. Enter the names of two users.

7. The application will display:

   * Shortest friendship path
   * Degree of Separation
   * Mutual Friends
   * Top 5 Most Connected Users
   * Graph visualization

---

# Technologies Used

* Python
* Breadth-First Search (BFS)
* NetworkX
* Tkinter
* Matplotlib
* Pandas
* CSV

---

# Author

**Elham Mosaad**

Faculty of Computers and Data Science

---

# Project Highlights

* Graph-based social network simulation.
* Efficient shortest-path computation using BFS.
* Interactive graphical user interface.
* Friendship analysis and visualization.
* Practical implementation of graph traversal algorithms.

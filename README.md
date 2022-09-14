![cover](https://github.com/KharbandaBhavy/Artificial_Intelligence_Project/blob/16f47be83a03b58ea389b6d19e35f9cfbc199e74/Execution.png)

<div align="center">
	<h2>Analysis and Visualization of Path Finding Algorithms (A* Algorithm)</h2>
</div>

## 🤖 Features of the project

- It is capable of visualizing the A* path finding algorithm using python and pygame.

## ⚒️ Project Details
- This project is completely based on `pygame` which is a library available in python. 
- Pygame is a set of Python modules designed for writing video games. Pygame adds functionality on top of the excellent SDL library. This allows you to create fully featured games and multimedia programs in the python language.

## 📈 A* Algorithm Introduction
- It is a searching algorithm that is used to find the shortest path between an initial and a final point.

- It is a handy algorithm that is often used for map traversal to find the shortest path to be taken. A* was initially designed as a graph traversal problem, to help build a robot that can find its own course. It still remains a widely popular algorithm for graph traversal.

- It searches for shorter paths first, thus making it an optimal and complete algorithm. An optimal algorithm will find the least cost outcome for a problem, while a complete algorithm finds all the possible outcomes of a problem.

- Another aspect that makes A* so powerful is the use of weighted graphs in its implementation. A weighted graph uses numbers to represent the cost of taking each path or course of action. This means that the algorithms can take the path with the least cost, and find the best route in terms of distance and time.

## 💹 A* Algorithm 
- The open list must be initialized. 
- Put the starting node on the open list (leave its f at zero). Initialize the closed list. 
- Follow the steps until the open list is non-empty:
1. Find the node with the least f on the open list and name it “q”.
2. Remove Q from the open list.
3. Produce q's eight descendants and set q as their parent.
4. For every descendant:
- If finding a successor is the goal, cease looking

- Else, calculate g and h for the successor.

1. successor.g = q.g + the calculated distance between the successor and the q.

2. successor.h = the calculated distance between the successor and the goal. We will cover three heuristics to do this: the Diagonal, the Euclidean, and the Manhattan heuristics.

3. successor.f = successor.g plus successor.h

- Skip this successor if a node in the OPEN list with the same location as it but a lower f value than the successor is present.

- Skip the successor if there is a node in the CLOSED list with the same position as the successor but a lower f value; otherwise, add the node to the open list end (for loop).

- Push Q into the closed list and end the while loop.

## 🛠️ Installation Steps

1. Download the `Artificial_Intelligence_Project` directory.
2. Unzip the downloaded file and navigate to the working directory.
3. Install dependencies

```bash
pip install pygame
```
4. Run the program


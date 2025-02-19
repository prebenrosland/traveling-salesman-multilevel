# Traveling Salesperson Problem (TSP) Using Multilevel Local Search

This project solves the Traveling Salesperson Problem (TSP) using an iterative clustering approach. The solution is structured into different levels of clustering, and a cost function evaluates the total distance traveled.

### Features

- Supports multi-level clustering:

  - **Level 2**: Clusters contain pairs of city pairs (4 cities).

  - **Level 1**: Clusters contain city pairs.

  - **Level 0**: A flat list of cities.

- Implements a cost function to calculate the total distance of a tour.

- Uses randomized swapping to explore better solutions.

### Installation

Clone the repository:

```sh
git clone https://github.com/prebenrosland/traveling-salesman-multilevel.git
```
Install dependencies if required:
```sh
pip install numpy
```

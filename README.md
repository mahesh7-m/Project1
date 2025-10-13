# N Queens Simulator ♛

An interactive web app that visualizes the **N-Queens problem** using **backtracking**.  
You can watch how the algorithm places queens, detects conflicts, and backtracks to find all valid solutions for a given N.

## 🌐 Live Demo
Try it out here → [N Queens Simulator](https://nqueens-mahesh-mahajan.vercel.app/)

## 🎥 Demo Video

<video src="https://github.com/mahesh7-m/N-Queens-Visualizer/raw/main/nqueens.mp4" width="720" controls>
  Your browser does not support the video tag.
</video>


## ✨ Features
- Choose board size (N)
- Visualize the backtracking algorithm step-by-step
- Watch queens being placed and removed dynamically
- See how conflicts are detected on rows, columns, and diagonals
- Display multiple solutions
- Adjustable animation speed
- Clean and responsive UI

## 🧠 Tech Stack
- HTML5
- CSS3
- JavaScript

## ⚙️ Algorithm Overview
The project uses **backtracking** to solve the N-Queens problem.
1. Place a queen in a row.
2. Check if the position is safe (no conflicts in column or diagonals).
3. If safe, move to the next row.
4. If not, backtrack and try another position.
5. Continue until all queens are placed or all possibilities are exhausted.

# CPU Scheduling Visualizer

A web-based simulator and visualizer for various CPU scheduling algorithms. This tool allows users to input processes and simulate their execution using different scheduling strategies, complete with animated Gantt charts and performance metrics.

## ✨ Features

- Supports the following CPU scheduling algorithms:
  - FCFS (First Come First Serve)
  - SJF (Shortest Job First)
  - SRTF (Shortest Remaining Time First)
  - Round Robin
  - Priority (Non-Preemptive)
  - Priority (Preemptive)

- Interactive process table for inputting arrival, burst, and (optional) priority values and time quantum

- Dynamic Gantt chart animation

- Displays process statistics (turnaround time, waiting time)

- Modern, responsive UI with dark theme

## 🖥️ Live Preview

It's simple. Open `main.html` in your browser.

## 📂 Project Structure
```
Scheduling Algorithms
  ├── index.js # Core logic and animation for simulation
  ├── main.html # UI layout and algorithm info cards
  ├── style.css # Modern and responsive styling
```

2. Open in Browser
No server needed. Simply open main.html in any modern browser (Chrome, Firefox, Edge).

## How to Use
-Choose a scheduling algorithm.

- Enter process details: arrival time, burst time, and priority and time quantum (if applicable).

- Add or remove processes using the + and - buttons.

- Click "Simulate" to run the animation and view statistics.

## 📊 Technologies Used
- HTML5

- CSS3 (custom and responsive design)

- JavaScript

# 📚 Concepts Illustrated
- CPU process scheduling

- Preemptive vs Non-preemptive strategies

- Turnaround time and waiting time calculations

- Real-time visualization and animation techniques

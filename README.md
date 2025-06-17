# Smart City Waste Collection Route Optimization

This project implements a smart waste collection system for urban environments, focusing on optimizing the routes of waste collection trucks based on bin fill levels and sector data.

## 🚚 Project Overview

The system reads data from various files (such as bin fill levels, sector information, and truck driver assignments) and uses graph algorithms to determine the most efficient routes for waste collection. The goal is to minimize travel distance and time, ensuring timely waste collection and efficient resource utilization.

## 📁 File Structure

- **main.cpp**: Main program logic and entry point.
- **Graph.h**: Graph data structure and algorithms for route optimization.
- **Minheap.h**: Min-heap implementation used in shortest path algorithms.
- **Location.h**: Location data structure for bins and sectors.
- **Pairs.h**: Utility for handling pairs of data.
- **Users.h**: User and driver management.
- **Headers.h**: Common includes and definitions.
- **getch.h**: Utility for input handling.
- **Binfill.txt**: Contains current fill levels of waste bins.
- **FSector.csv**: Sector information for the city.
- **controller.csv**: Controller data for managing operations.
- **truckdriver.csv**: Truck driver assignments and information.

## 🛠️ How to Build

1. Make sure you have a C++ compiler installed (e.g., g++, clang++).
2. Compile the project:
   ```sh
   g++ main.cpp -o waste-optimizer
   ```
   Make sure all header files are in the same directory or update include paths as needed.

## 🚀 How to Run

1. Ensure all data files (`Binfill.txt`, `FSector.csv`, etc.) are present in the project directory.
2. Run the executable:
   ```sh
   ./waste-optimizer
   ```
3. Follow the on-screen instructions to perform route optimization and view results.

## 📊 Features

- Reads real-time bin fill data and sector information.
- Assigns trucks and drivers efficiently.
- Calculates optimal collection routes using graph algorithms.
- Outputs optimized routes and collection schedules.

## 👨‍💻 Authors

- Mirza Humayun Masood

## 📜 License

This project is for educational purposes. Please contact the author for other uses.

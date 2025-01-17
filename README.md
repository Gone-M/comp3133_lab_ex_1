# 📘 COMP 3133 - Lab 01: Reading CSV Files using Streams

Welcome to **Lab 01**! This project focuses on reading and processing a CSV file using **Node.js** and its `fs` and `csv-parser` modules. The task demonstrates my understanding of working with streams and file operations in Node.js.

## 🛠️ Project Overview

This lab involves:
1. Creating a **Node.js** project named `Lab01_StudentID_COMP3133`.
2. Installing the required module: `csv-parser`.
3. Reading and processing a CSV file (`input_countries.csv`) to:
   - Delete `canada.txt` and `usa.txt` files if they already exist.
   - Filter rows based on the country (`Canada` or `United States`) and write them to their respective output files (`canada.txt` and `usa.txt`).

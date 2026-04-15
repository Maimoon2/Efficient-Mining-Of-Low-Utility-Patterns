# Efficient Mining of Low Utility Patterns (LUSPM)

## 📌 Project Description

This project implements the Low Utility Sequence Pattern Mining (LUSPM) algorithm in Java. Unlike traditional pattern mining, which focuses on high-utility patterns, this algorithm identifies low-utility sequential patterns that can still provide valuable insights.

The project includes both a naive baseline implementation and an optimized version using pruning techniques to reduce the search space.

## ⚙️ Technologies Used

* Java
* IntelliJ IDEA
* Maven

## 📂 Project Structure

* `MainLUSMAlgorithm.java` → Main class to run the program
* `LowUtilitySequenceMining.java` → Optimized algorithm implementation
* `LUSM_naive.java` → Naive baseline algorithm
* `MemoryLogger.java` → Tracks memory usage
* `resources/` → Contains dataset files

## ▶️ How to Run

1. Open the project in IntelliJ IDEA
2. Navigate to `MainLUSMAlgorithm.java`
3. Select a dataset from the `resources` folder
4. Run the program

## 📊 Results

* The algorithm works efficiently for small datasets
* Execution time increases for large datasets due to exponential growth of candidate sequences
* Pruning techniques help reduce unnecessary computations

## ⚠️ Observations

* Naive approach is slower compared to optimized version
* Performance depends on dataset size and parameters

## 🔗 Reference

This project is based on the implementation provided by:
https://github.com/Zhidong-Lin/LUSPM

Modifications were made to:

* Run the code locally
* Convert output to English
* Analyze performance on different datasets

## 👤 Author

Maimoon Zahid
Registration Number: 23BDS0188


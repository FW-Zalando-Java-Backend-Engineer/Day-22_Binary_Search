# **📘 Day-22: Arrays & Binary Search in Java**

Welcome to **Day-22** of our Java backend journey! Today, we leveled up with one of the most efficient algorithms in computer science: **Binary Search**, combined with Java’s foundational concept — **Arrays**.

From number guessing games to simulating medical diagnoses and movie filters, we saw how Binary Search powers **real-world decision systems**. 🔍🎯

---

## **📌 Lesson Structure**

### **1️⃣ Java Arrays Refresher**

* Arrays are **fixed-size**, indexed containers that store values of a specific type.
* Arrays must be **sorted** before applying Binary Search.

---

## **📂 Concept Visualizations**

### **🔍 Binary Search (Divide & Conquer)**

A powerful search algorithm that reduces search space by **half every time**.

#### 📊 Visualization:

```
Sorted Array (by severity or rating):

Index:     0     1     2     3     4     5
         [1]   [2]   [3]   [3]   [4]   [5]

Goal: Find all values == 3

1️⃣ Start at middle → index 2
2️⃣ Found a match → expand left & right
3️⃣ Collect all matches → [3, 3]
```

#### Operation Cost:

* **Time Complexity**: `O(log n)` to find one match
* **Expansion**: `O(k)` where `k` = number of matching entries

---

## **🔬 Real-World Projects**

### 🧪 Project 1: 🎯 Guess the Number (Binary Search Game)

* Simulates how Binary Search works in the classic Hi-Lo game.
* Great for showing divide-and-conquer logic interactively.

### 🧪 Project 2: 🏥 Health Diagnosis Simulator

* A sorted list of diseases by severity.
* User enters symptom severity (1–3), and the system returns **all possible diagnoses**.
* Demonstrates **Binary Search + Left/Right Expansion**.

### 🧪 Project 3: 🎬 Movie Matcher

* List of movies sorted by rating (1 to 5).
* Binary Search finds **all movies** that match the input rating.
* Includes:

  * Clean UI via console
  * Modular code using static methods
  * Realistic simulation of rating-based filtering

---

## **🧠 Key Concepts Practiced**

| Topic                   | Covered? |
| ----------------------- | -------- |
| Arrays                  | ✅        |
| Binary Search Logic     | ✅        |
| Real-world Mapping      | ✅        |
| Debugging with IntelliJ | ✅        |
| Scanner Input Handling  | ✅        |
| Refactoring to Methods  | ✅        |
| Matching Multiple Items | ✅        |

---

## **🧪 Debugging Exercise**

We used IntelliJ IDEA’s debugger to:

* Track `low`, `high`, and `mid` values
* Step through binary search logic
* See how search space shrinks and matches are collected

---

## **🎯 Practice Challenge**

### 🔧 Assignment: **Movie Matcher**

> Build your own MovieMatcher app where the user can:

* Add movies (title + rating)
* Search for all movies with a specific rating using **Binary Search**
* Display all current movies

**Bonus:** Sort the array using Bubble Sort before search if it's not pre-sorted.

---

## **📚 Additional Resources**

* [Binary Search on GeeksForGeeks](https://www.geeksforgeeks.org/binary-search/)
* [Baeldung: Arrays in Java](https://www.w3schools.com/java/java_arrays.asp)
* [Java Advanced Sorting](https://www.w3schools.com/java/java_advanced_sorting.asp)

---

## **🎥 Video Lesson Recording**

📺 [*Watch the Day-22 Session Here*](https://us06web.zoom.us/rec/share/fTD3RNRO2BvRH6VgPkp_4UgXOiqwzaJfEqAkXiPMJhCIuUN5GHnJBAAQBmq_94ux.NoAIPJClS7xpf1fd?startTime=1744701336000)

---

🚀 **Fantastic work today! Binary Search is a must-know tool in your developer arsenal.** 😄



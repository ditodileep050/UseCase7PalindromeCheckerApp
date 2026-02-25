# UseCase7 – Deque Based Optimized Palindrome Checker

## 🧠 Objective
Demonstrate palindrome validation using a Deque (Double Ended Queue) by comparing front and rear elements directly.

---

## 🎯 Goal
Use a Deque to efficiently compare the first and last characters of a string without creating a reversed copy.

---

## 🔄 Flow of Execution

1. Define the input string  
2. Insert each character into a Deque  
3. Remove first and last elements  
4. Compare both characters  
5. Continue until deque becomes empty or mismatch occurs  
6. Display the result  

---

## 📚 Key Concepts Used

### Deque (Double Ended Queue)
A data structure that allows insertion and deletion from both the front and rear.

### Front and Rear Access
- `removeFirst()` → Removes element from the front  
- `removeLast()` → Removes element from the rear  

### Optimized Data Handling
This approach eliminates the need for:
- Extra reversal strings  
- Separate stack or queue structures  

It performs direct symmetric comparison.

---

## 🛠 Data Structure Used
- Deque (ArrayDeque implementation)

---

## ⚙️ How to Run

### Compile:
```
javac UseCase7PalindromeCheckerApp.java
```

### Run:
```
java UseCase7PalindromeCheckerApp
```

---

## 📌 Example

### Input
```
refer
```

### Output
```
Input : refer
Is Palindrome? : true
```

---

## 🚀 Learning Outcome

This use case helps understand:

- Bidirectional data access
- Efficient symmetric comparison
- Optimization over stack/queue approach
- Reduced auxiliary space usage

---

## 👨‍💻 Author

Dito Dileep  
B.Tech Computer Science (AI & ML)  
SRM Institute of Science and Technology

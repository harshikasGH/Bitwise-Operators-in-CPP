# 💻 Bitwise Operators in C++

## 🎯 Aim  
To perform bitwise operations and demonstrate how to set and reset a specific bit in an integer.

---

## 📚 Theory

Bitwise operators operate directly on the binary representation of integers.  
They are essential for tasks like flag manipulation, low-level programming, and performance optimization.

### 🔹 Bitwise AND (`&`)
Sets each bit to 1 only if both corresponding bits are 1.  
**Example:**  
`5 & 3` → `0101 & 0011` = `0001` → **Result:** `1`

### 🔹 Bitwise OR (`|`)
Sets each bit to 1 if at least one of the corresponding bits is 1.  
**Example:**  
`5 | 3` → `0101 | 0011` = `0111` → **Result:** `7`

### 🔹 Bitwise XOR (`^`)
Sets each bit to 1 only if the corresponding bits are different.  
**Example:**  
`5 ^ 3` → `0101 ^ 0011` = `0110` → **Result:** `6`

### 🔹 Bitwise NOT (`~`)
Inverts all bits of an integer.  
**Example:**  
`~5` → `~0101` = `...1010` → **Result:** `-6` (in two's complement representation)

### 🔹 Left Shift (`<<`)
Shifts bits to the left, multiplying the number by powers of 2.  
**Example:**  
`5 << 1` → `0101 << 1` = `1010` → **Result:** `10`

### 🔹 Right Shift (`>>`)
Shifts bits to the right, dividing the number by powers of 2.  
**Example:**  
`5 >> 1` → `0101 >> 1` = `0010` → **Result:** `2`

---

## 🧠 Additional Insights

- Bitwise operators are often used within control structures like `if`, `while`, and `switch` to manipulate data efficiently.
- They are especially useful in scenarios where multiple flags or states are stored compactly in a single variable.
- Common applications include embedded systems, graphics programming, encryption, and performance-critical logic.

---

## ✅ Conclusion

Bitwise operators unlock a layer of programming precision that goes beyond standard arithmetic.  
Whether you're shifting bits or toggling flags, these operations empower efficient, low-level data handling.  
From optimizing performance to encoding logic with elegance, bitwise mastery is a hidden superpower in every programmer’s toolkit.

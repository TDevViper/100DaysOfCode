# 🧠 #100DaysOfCode — Day 7 (C Language: Data Structures Focus)

---

## 1️⃣ Stack (Array Implementation)

✅ Created fixed-size stack using `#define MAX`  
✅ Used `top` variable to manage stack  

**Functions Implemented:**
- `initialize()` → set `top = -1`
- `isEmpty()` / `isFull()`
- `push()` → `stack[++top] = val`
- `pop()` → `return stack[top--]`
- `peek()` → view `stack[top]`
- `display()` → loop from `top` to `0`

🧩 **Concept Learned:** LIFO (Last In, First Out)

---

## 2️⃣ Stack (Linked List Implementation)

✅ Used `struct Node` with `data` + `next`  
✅ Implemented stack dynamically  

**Functions Implemented:**
- `push()` → new node added at head (top)  
  → `newNode->next = top; top = newNode;`
- `pop()` → remove head → `top = top->next`
- `peek()` → return `top->data`

🧩 **Concept Learned:** Dynamic stack (no overflow), uses pointers & memory allocation

---

## 3️⃣ Queue (Array Implementation)

✅ Used `front` and `rear` indices  

**Functions Implemented:**
- `enqueue()` → add element at rear → `q[++rear] = val;`
- `dequeue()` → remove element from front → `val = q[front++];`
- `isFull()` & `isEmpty()`

🧩 **Concept Learned:** FIFO (First In, First Out) using arrays

---

## 4️⃣ Queue (Linked List Implementation)

✅ Used two pointers: `front`, `rear`  

**Functions Implemented:**
- `enqueue()` → insert node at rear → `rear->next = n; rear = n;`
- `dequeue()` → delete node from front → `front = front->next;`

🧩 **Concept Learned:** Dynamic queue with flexible size

---

## 💡 Key Concepts Reinforced Today

| Concept | Meaning | Example |
|----------|----------|----------|
| Stack (LIFO) | Last in → First out | Function calls, Undo feature |
| Queue (FIFO) | First in → First out | Printer queue, Processes |
| Array vs Linked List | Static vs Dynamic memory | Stack/Queue in both |
| Pointers & malloc() | Dynamic node allocation | Used in linked lists |

---

## ⚙️ Mini Skills Practiced
✅ Writing modular functions in C  
✅ Using global variables like `top`, `front`, `rear`  
✅ Memory management with `malloc()` and `free()`  
✅ Traversing linked lists with `while(temp != NULL)`  
✅ Handling overflow & underflow conditions  

---

## 🏁 Day Summary
**Learning Tagline:**  
> “Today I built and understood Stack & Queue — the backbone of Data Structures in C.”



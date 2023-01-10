# 1. Course Introduction

- How to invent efficient solutions to unsolved problems using algorithms and data structures.
- Algorithm  = A program that solves a problem.
- Algorithms requires resources...
- The resources are often the data structures or common patterns in the problem.
- In real technical interview, just need to show that you can successfully understand the concepts behind it.
- Use this course as a starting place, and explore more on my own.

# 2. Course Outline

1: Introduction and Efficiency
  - Course Introduction
  - Syntax
  - Efficiency
  - Notation of Efficiency
 
2: List-Based Collections
  - Lists/Arrays
  - Linked Lists
  - Stacks
  - Queues
 
3: Searching and Sorting
  - Binary Search
  - Recursion
  - Bubble Sort
  - Merge Sort
  - Quick Sort

4: Maps and Hashing
  - Maps
  - Hashing
  - Collisions
  - Hashing Conventions

5: Trees
  - Trees
  - Tree Traversal
  - Binary Trees
  - Binary Search Trees
  - Heaps
  - Self-Balancing Trees

6: Graphs
  - Graphs
  - Graph Properties
  - Graph Representation
  - Graph Traversal
  - Graph Paths

7: Case Studies in Algorithms
  - Shortest Path Problem
  - Knapsack Problem
  - Traveling Salesman Problem
 
8: Technical Interview Tips
  - Mock Interview Breakdown
  - Additional Tips
  - Practice with Pramp
  - Next Steps

# 3. Course Expectations

What are you hoping to learn from this course? Do any of the topics seem particularly interesting?
- data structures and algorithms
- make my code more efficient

# 4. Syntax
...

# 5. Python Practice

```python
"""You can use this class to represent how classy someone
or something is.
"Classy" is interchangable with "fancy".
If you add fancy-looking items, you will increase
your "classiness".
Create a function in "Classy" that takes a string as
input and adds it to the "items" list.
Another method should calculate the "classiness"
value based on the items.
The following items have classiness points associated
with them:
"tophat" = 2
"bowtie" = 4
"monocle" = 5
Everything else has 0 points.
Use the test cases below to guide you!"""

class Classy(object):
    def __init__(self):
        self.items = []
    def addItem(self,string):
        self.items.append(string)
    def getClassiness(self):
        sum = 0
        for item in self.items:
            if item == "tophat":
                sum += 2
            elif item == "bowtie":
                sum += 4
            elif item == "monocle":
                sum += 5
        return sum

# Test cases
me = Classy()

# Should be 0
print me.getClassiness()

me.addItem("tophat")
# Should be 2
print me.getClassiness()

me.addItem("bowtie")
me.addItem("jacket")
me.addItem("monocle")
# Should be 11
print me.getClassiness()

me.addItem("bowtie")
# Should be 15
print me.getClassiness()
```

# 100 Days Of Code - Learning Log

### Day 1: April 27

**Today's Progress**  
- I studied Unittest and Logging from the course [Python 3 Introduction + Application + Silicon Valley Coding Style Taught by an Active Silicon Valley Engineer](https://www.udemy.com/course/python-beginner/).

**Thoughts**  
- I learned the basics, such as how using `pytest` can make test code simpler and more convenient, the relationship between error levels and logging, and how to pass loggers to other modules.

**Link**  
[Python 3 Introduction + Application + Silicon Valley Coding Style Taught by an Active Silicon Valley Engineer](https://www.udemy.com/course/python-beginner/)


### Day 2: April 28

**Today's Progress**  
- Based on what I studied yesterday, I wrote code by myself to review and deepen my understanding. 
- Specifically, I created a simple class to implement payment functionality, and wrote test cases using both `unittest` and `pytest`. 
- I also successfully output logs to a file using `logging` and `logger`.

**What I Learned?**  
- I realized that while watching Udemy videos, I only *felt* like I understood the concepts. 
- By actually writing code myself while asking ChatGPT questions, I was able to gain a much deeper understanding of how to use the concepts in practice.

**Link**  
[Python 3 Introduction + Application + Silicon Valley Coding Style by a Current Silicon Valley Engineer](https://www.udemy.com/course/python-beginner/)


### Day 3: April 29

**Today's Progress**  
- Today, I built the core domain models for a group payment and bill-splitting system.  
- Specifically, I defined data models such as `User`, `Payment`, `Asset`, and `Debt`, and created collection classes to manage lists of these models.  
- I also implemented logic to summarize and resolve user debts and assets safely using Pydantic.

**What I Learned?**  
- Designing the domain layer from scratch made me realize how important it is to think deeply about data structures and responsibility separation.  
- It also helped me better understand how to build a solid foundation for future API and frontend integrations.

**Link**  
[walicaaa-backend GitHub Commit](https://github.com/takuto-san/walicaaa-backend/commit/89feb00b888489350b104c6af4e7a2ecbd903a4d)


### Day 4: April 30

**Progress**  
- Edited the schema for payments and settlements, and added logic to calculate balances and generate settlements.  
- Now the system can automatically determine who should pay how much to whom based on all users' payment history.

**Thoughts**  
- I struggled with Pydantic—it was hard to follow how types were enforced in data passing throughout the code.

**Link**  
[walicaaa-backend GitHub commits](https://github.com/takuto-san/walicaaa-backend/commits/main/?since=2025-05-01&until=2025-05-01)


### Day 5: May 1

**Today's Progress**  
- Worked on Assignment 3 of the "Deep Learning Fundamentals 2025" course by Matsuo Lab.  
- Studied MLPs (Multi-Layer Perceptrons) and built a model for image recognition.

**What I Learned?**  
- By implementing an AI model from scratch in a Python script in addition to the assignment, I was able to deepen my understanding.  
- Used a publicly available Kaggle dataset of soccer player face images to train a model on the faces of eight players, including Messi and Ronaldo.


### Day 6: May 2

**Today's Progress**  
- I started using Cisco Packet Tracer to study networking.
- Since it was my first day, I worked through the tutorial sections.

**What I Learned?**  
- Compared to studying theoretical concepts like the OSI reference model, I found - it more engaging and less tedious to actually build networks on the screen.Hands-on learning made it easier and more enjoyable.


### Day 7: May 3

**Today's Progress**  
- Solved two problems from LeetCode’s Top Interview 150.
- Since my computer science tasks were starting to pile up, I organized and prioritized them.

**What I Learned?**  
- I want to continue studying computer science every day to strengthen my foundational skills, while sharing my progress using #100DaysOfCode.
- To start, I plan to work through each task based on how much time I actually have each day.


### Day 8: May 4

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150.
- Watched the first lecture video of "Create Your Own OS from Scratch".
- Installed XQuartz → Set up DevContainer(Docer) → Create a FAT image(disk.img) → Saved it as BOOTX64.EFI → Booted EFI using QEMU

**What I Learned?**  
- Although I just folloed the commands, using a Docker image made the environment setup smooth and convenient.
- I tried to reproduce the process of how a computer boots and starts working, but honestly, I didn't really understand what was happning.


### Day 9: May 5

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150.
- Watched the second lecture video of "Create Your Own OS from Scratch".
- Built UEFI app using EDK II.

**What I Learned?**  
- It took time because of a "Directory not found" error
- I'm glad I was able to get "Hello, Mikan World!" to output with help from ChatGPT


### Day 10: May 6

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Watched Lecture 3 of "Create Your Own OS from Scratch"
- Created a kernel file
- Reviewed content from Lecture 1 and 2 by re-reading the textbook and doing additional research

**What I Learned?**  
- I now understand how firmware processes work up to the point where a binary file is executed and "Hello, world!" is displayed on XQuarz
- I understood the difference between displaying "Hello, world" by executing a manually written binary and by runnig a program written in C


### Day 11: May 7

**Today's Progress**  
- Completed the Lecture 4 assignment for the “Deep Learning Basics” course at Matsuo Lab, University of Tokyo.
- Independently built a soccer-player face-recognition model to reinforce my understanding of the lecture content.

**What I Learned?**  
- Parameter initialization techniques (e.g. Xavier, He)
- Normalization methods (e.g. BatchNorm, input standardization)
- Optimization algorithms (e.g. SGD, Adam)
- Regularization strategies (e.g. L1/L2 weight decay, Dropout)

### Day 12: May 8

**Today's Progress**  
- Solved three problems from LeetCode’s Top Interview 150:
    - Jump Game (Greedy)
    - Jump Game II (Greedy / BFS-style)
    - H-Index (Sort + Greedy)

**What I Learned?**  
- How to apply Greedy algorithms to interval-reach problems
- A BFS-style layer-by-layer approach for minimizing jumps
- The definition and computation of the H-Index metric


### Day 13: May 9

**Today's Progress**  
- Solved a problem from LeetCode's Top Interview 150
- Progressed Lecture 4 of "Create Your Own OS from Scratch"

**What I Learned?**  
- How to append and remove elements from a list in O(1) time
- How to automate the build process useing the make command (including compilation and linking)


### Day 14: May 10

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150

**What I Learned?**  
- How to use cumulative product techniques and greedy strategies for solving array-based problems efficuently


### Day 15: May 11

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Progressed Lecture 5 of "Create Your Own OS from Scratch"

**What I Learned?**  
- Learned how to calculate amount of trapped water between blocks using the two-ponter and greedy strategies
- Understood how to update left and right maximum heights to efficiently compute water volume 


### Day 16: May 12

**Today's Progress**  
- Solves two problems from LeetCode's Top Interview 150

**What I Learned?**  
- Practiced converting integers to Roman numerals
- Learned that some values (like 4,9,40,etc.) require special subtraction-based notation (e.g., IV,IX,XL), which made the problem a bit tricky


### Day 17: May 13

**Today's Progress**
- Solved two problems from LeetCode's Top Interview 150
- Progressed Lecture 6 (a, b) of "Create Your Own OS from Scratch"

**What I Learned?**  
- Practiced solving problems involving string operations:
    - 58 Length of Last Word
    - 14 Longest Common Prefix
- I’ve reached a point where I can now solve most Easy-level problems on my own.
- Encountered build errors due to mismatched field names between kernel (C++) and UEFI (C):
- Understood the program that detects PCI devices.


### Day 18: May 15

**Today's Progress**
- Solves two problems from LeetCode's Top Interview 150
- Completed the Lecture 5 assingnment for the "Deep Learning Basics" course at Matsuo Lab, University of Tokyo

**What I Learned?**  
- Learned about CNN
- Practiced solving problems involving string operation:
    - 151 Reverse Words in a String（Two Pointers, List/Stack Usage）
- I was on the right track by scanning from the end and extracting words, but the code became unnecessarily verbose.
- Realized it's important to first translate the essential logic into code before trying to handle edge cases
- For example, in this case, the first thing to do is trim the trailing spaces and find the index of the last character
, so I should focus on implementing that part first
- Learned how to implement CNN


### Day 19: May 16

**Today's Progress**
- Solves two problems from LeetCode's Top Interview 150

**What I Learned?**  
- Practiced solving problems involving string operation: 
    - 6 Zigzag Conversion
    - 28 Find the Index of the First Occurrence in a String


### Day 20: May 19

**Today's Progress**
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 6 (b,c) of "Create Yor Own OS from Scratch"
- Solved four problems from LearnSQL.com's "SQL Practice"

**What I Learned?**  
LeetCode
- Practiced solving problems involving string operation and two pointer:
    - 125 Valid Palindrome
    - 68 Text Justification
LearnSQL.com
- Chapter: 1.Recap of SQL JOIN types
  - Section: Simple JOINs recap
    4. Get to know the adaptation table
    5. JOINs – recap
    6. JOIN and filtering
    7. JOINS – ambiguous columns
- Got the cursor to move along with the mouse
- Learned how the OS detects PCI devices and access their registers


### Day 21: May 20

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Solved 22 problems from LearnSQL.com's "SQL Basic"

**What I Learned?**  
- Practiced solving problems involving two pointer:
    - 125 Valid Palindrome
    - 68 Text Justification
- Finished the chapter on JOIN 
- Learned how to use JOIN methods: INNER, OUTER, RIGHT, LEFT


### Day 22: May 21

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150

**What I Learned?**  
- Practiced solving problems involving two pointer:
    - 111 Container With Most Water
    - 15 3Sum
- Understood when to use sorting and how to handle 3 valiables using pointer


### Day 23: May 22

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Solved 22 problems from LearnSQL.com's "SQL Basic"
- Implemented an AI model using CNN to recognize soccer players' faces
(review of Lecture 5 from the "Deep Learning Basics" course at Matsuo Lab, University of Tokyo)

**What I Learned?**  
- Practiced solving problems involving sliding window:
    - 3 Longest Substring Without Repeating Characters
    - 209 Minimum Size Subarray Sum
- Learned how to use a set to check for the occurrence of elements
- Finished the chapter on 2.Selecting from one table


### Day 24: May 23

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 7 of "Create Yor Own OS from Scratch"

**What I Learned?**  
- Practiced solving problems involving sliding window:
    - 30 Substring with Concatenation of All Words
    - 76 Minimum Window Substring
- Learned how to move the mouse via interrupt handling.
- Improved interrupt handler speed by using a FIFO instead of polling.


### Day 25: May 25

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150

**What I Learned?**  
- Practiced solving problems involving matrix:
    - 36 Valid Sudoku
    - 54 Spiral Matrix


### Day 26: May 26

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 8 of "Create Yor Own OS from Scratch"
- Solved 48 problems from LearnSQL.com's "SQL Basic"


**What I Learned?**  
- Practiced solving problems involving matrix:
    - 48 Rotate Image
    - 73 Set Matrix Zeroes
- Learned about memory management  
- Learned how to retrieve physical memory usage and how to allocate and free memory
- Made progress in the following chapters of 'SQL Basic'
    - 3.Querying more than one table (13/13)
    - 4.Aggregation and grouping (23/23)
    - 6.Subqueries (12/22)


### Day 27: May 27

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 11 (a,b,c,d) of "Create Yor Own OS from Scratch"


**What I Learned?**  
- Practiced solving problems involving matrix and hashmap:
    - 289 Game of Life
    - 383 Ransom Note
- In order to run multiple timers concurrently, I set the Local APIC timer to operate in periodic mode, causing it to generate regular interrupts

 
### Day 28: May 28

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150

**What I Learned?**  
- Practiced solving problems involving hashmap:
    - 205 Isomorphic Strings
    - 290 Word Pattern


### Day 29: May 29

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the Lecture 6 assingnment for the "Deep Learning Basics" course at Matsuo Lab, University of Tokyo

**What I Learned?**  
- Practiced solving problems involving hashmap:
    - 242 Valid Anagram
    - 49 Group Anagrams


### Day 30: May 30

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 11 (e), 13, 14（a,b） of "Create Yor Own OS from Scratch"

**What I Learned?**  
- Practiced solving problems involving hashmap:
    - 1 Two Sum
    - 202 Happy Number
- Enabled concurrent execution of tasks with multiple contexts using preemptive multitasking
- Classified tasks into running, runnable, and waiting states with assigned priority levels


### Day 31: May 31

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 14（c,d）, 17 of "Create Yor Own OS from Scratch"

**What I Learned?**  
- Practiced solving problems involving hashmap:
    - 219 Contains Duplicate II
    - 128 Longest Consecutive Sequence
- Learned abourt file systems
- Used UEFI's Block I/O Protocol to implement the full flow:
create a volume image → load it via an EFI bootloader → pass it to the kernel
- Built on that to enable an ls command in the terminal


### Day 32: June 2

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 18, 19 of "Create Yor Own OS from Scratch"

**What I Learned?**  
- Practiced solving problems involving Intervals:
    - 228 Summary Ranges
    - 56 Merge Intervals
- Implementeda program corresponding to the cat command by understanding the FAT structure and opening files in the terminal
- Added an executable file to the volume image and implemented a calculator application
- Learned about paging, which maps virtual addresses to physical adresses


### Day 33: June 3

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 20 of "Create Yor Own OS from Scratch"

**What I Learned?**  
- Practiced solving problems involving Intervals:
    - 57 Insert Interval
    - 452 Minimum Number of Arrows to Burst Balloons
- Learned about system calls
- Understood how to set privilege levels for memory access and restrict which OS functions applications can use


### Day 34: June 5

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Studied Lecture 7 of the "Deep Learning Basics" course at Matsuo Lab, University of Tokyo

**What I Learned?**  
- Practiced solving problems involving Stack:
    - 20 Valid Parentheses
    - 71 Simplify Path
- Learned about RNN
- Understood how a neural network retains context using timeseries data

### Day 35: June 6

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 1,2 of "Create Yor Own OS from Scratch"（Second round）

**What I Learned?**  
- Practiced solving problems involving Stack:
    - 150 Evaluate Reverse Polish Notation
    - 155 Min Stack
- Reviewed how to launch BOOTX64.EFI(the executable file) using QEMU
- Retrived the memory map using UEFI and EDKII features
- Gained a basic understanding of pointers
- Transcribed the lecture code to follow and understand its execution flow


### Day 36: June 7

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 3a of "Create Yor Own OS from Scratch"（Second round）
- Completed sections 1.1~1.3 of the Cisco Networking Academy’s “Networking Basics” course

**What I Learned?**  
- Practiced solving problems involving Stack and Linked List:
    - 224 Basic Calculator
    - 141 Linked List Cycle
- Reviewed how to retrieve the memory map using UEFI Boot Services
- Studied an overview of networking fundamentals

### Day 37: June 9

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 3 (b,c,d) 4 (a,b,c) of "Create Yor Own OS from Scratch"（Second round）

**What I Learned?**  
- Practiced solving problems involving Linked List:
    - 2 Add Two Numbers
    - 21 Merge Two Sorted Lists
- Reviewed how to draw pixels
- Deepened my understanding of pointers by examining the assembly output of compiled C++ code

### Day 38: June 10

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 4 (d) of "Create Yor Own OS from Scratch"（Second round）

**What I Learned?**  
- Practiced solving problems involving Linked List:
    - 92 Reverse Linked List II
    - 138 Copy List with Random Pointer
- Learned how to copy and reverse linked lists
- Reviewed how to load an EFL-format kernel file into memory

### Day 39: June 11

**Today's Progress**  
- Solved a problem from LeetCode's Top Interview 150
- Completed sections 1.4~2.2 of the Cisco Networking Academy’s “Networking Basics” course

**What I Learned?**  
- Practiced solving problem involving Linked List:
    - 25 Reverse Nodes in k-Group
- Learned how to solve problems about Reverse Nodes in k-Group
- Reviewed network components and basic communication methods (P2P and client-server systems)

### Day 40: June 12

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Submitted the assingment for Lecture 7 of the "Deep Learning Basics" course at Matsuo Lab, University of Tokyo

**What I Learned?**  
- Practiced solving problems involving Linked List:
    - 19 Remove Nth Node From End of List
    - 82 Remove Duplicates from Sorted List II

### Day 41: June 13

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Edited my Qiita article about the internship I participated last year

**What I Learned?**  
- Practiced solving problems involving Linked List:
    - 86 Partition List
    - 61 Rotate List

### Day 42: June 15

**Today's Progress**  
- Solved a problem from LeetCode's Top Interview 150
- Edited my Qiita article about the internship I participated last year

**What I Learned?**  
- Practiced solving a problem involving Linked List:
    - 146 LRU Cache
- Learned to solve it by mapping nodes to hash table

### Day 43: June 16

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 5 of "Create Yor Own OS from Scratch"（Second round）
- Completed module 1 of the Cisco Networking Academy’s “Exploring Networking with Cisco Packet Tracer” course

**What I Learned?**  
- Practiced solving a problem involving Binary Tree General:
    - 104 Maximum Depth of Binary Tree
    - 100 Same Tree
- Reviewed how to print a string to the console
- I was looking for learning resources for networking that use Cisco Packet Tracer and found a site that looks promising.
- I want to use either this site or Udemy to build a solid foundatin in practical networking.

### Day 44: June 17

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 6 (a) of "Create Yor Own OS from Scratch"（Second round）

**What I Learned?**  
- Practiced solving a problem involving Binary Tree General:
    - 226 Invert Binary Tree
    - 101 Symmetric Tree

### Day 45: June 19

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Submitted the assingment for Lecture 8 of the "Deep Learning Basics" course at Matsuo Lab, University of Tokyo

**What I Learned?**  
- Practiced solving a problem involving Binary Tree General:
    - 105 Construct Binary Tree from Preorder and Inorder Traversal
    - 106 Construct Binary Tree from Inorder and Postorder Traversal

### Day 46: June 20

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Progressed the section 6 (b) of "Create Yor Own OS from Scratch"（Second round）

**What I Learned?**  
- Practiced solving a problem involving Binary Tree General:
    - 117 Populating Next Right Pointers in Each Node II
    - 114 Flatten Binary Tree to Linked List

### Day 47: June 21

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 6 (b) of "Create Yor Own OS from Scratch"（Second round）

**What I Learned?**  
- Practiced solving a problem involving Binary Tree General:
    - 112 Path Sum
    - 129 Sum Root to Leaf Numbers

### Day 48: June 22

**Today's Progress**  
- Solved a problem from LeetCode's Top Interview 150

**What I Learned?**  
- Practiced solving a problem involving Binary Tree General:
    - 124 Binary Tree Maximum Path Sum

### Day 49: June 23

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 6 (c) of "Create Yor Own OS from Scratch"（Second round）
- Made progress in Section 2 of the Udemy course, "The Complete Course on Cisco Packet Tracer"

**What I Learned?**  
- Practiced solving a problem involving Binary Tree General:
    - 173 Binary Search Tree Iterator
    - 222 Count Complete Tree Nodes
- Practiced building simple networks
    - 9 Basic Device Configurations

### Day 50: June 24

**Today's Progress**  
- Solved two problems from LeetCode's Top Interview 150
- Completed the section 7 (a) of "Create Yor Own OS from Scratch"（Second round）
- Made progress in Section 2, 3 of the Udemy course, "The Complete Course on Cisco Packet Tracer"

**What I Learned?**  
- Practiced solving a problem involving Binary Tree General and BFS:
    - 236 Lowest Common Ancestor of a Binary Tree
    - 199 Binary Tree Right Side View
- Practiced building simple networks, and routing basics and static routing
    - 9 Basic Device Configurations
    - 10 Cabling in Packet Tracer
    - 11 IP & Subnetting Assigning
    - 12 Lab with one switch and PCs
    - 14 Introduction to routing and routers
    - 15 Dynamic and Static routing

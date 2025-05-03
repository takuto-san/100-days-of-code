# 100 Days Of Code - Learning Log

### Day 1: April 27, 2025

**Today's Progress**  
I studied Unittest and Logging from the course [Python 3 Introduction + Application + Silicon Valley Coding Style Taught by an Active Silicon Valley Engineer](https://www.udemy.com/course/python-beginner/).

**Thoughts**  
I learned the basics, such as how using `pytest` can make test code simpler and more convenient, the relationship between error levels and logging, and how to pass loggers to other modules.

**Link**  
[Python 3 Introduction + Application + Silicon Valley Coding Style Taught by an Active Silicon Valley Engineer](https://www.udemy.com/course/python-beginner/)


### Day 2: April 28, 2025

**Today's Progress**  
Based on what I studied yesterday, I wrote code by myself to review and deepen my understanding. Specifically, I created a simple class to implement payment functionality, and wrote test cases using both `unittest` and `pytest`. I also successfully output logs to a file using `logging` and `logger`.

**Reflections**  
I realized that while watching Udemy videos, I only *felt* like I understood the concepts. By actually writing code myself while asking ChatGPT questions, I was able to gain a much deeper understanding of how to use the concepts in practice.

**Link**  
[Python 3 Introduction + Application + Silicon Valley Coding Style by a Current Silicon Valley Engineer](https://www.udemy.com/course/python-beginner/)


### Day 3: April 29, 2025

**Today's Progress**  
Today, I built the core domain models for a group payment and bill-splitting system.  
Specifically, I defined data models such as `User`, `Payment`, `Asset`, and `Debt`, and created collection classes to manage lists of these models.  
I also implemented logic to summarize and resolve user debts and assets safely using Pydantic.

**Reflections**  
Designing the domain layer from scratch made me realize how important it is to think deeply about data structures and responsibility separation.  
It also helped me better understand how to build a solid foundation for future API and frontend integrations.

**Link**  
[walicaaa-backend GitHub Commit](https://github.com/takuto-san/walicaaa-backend/commit/89feb00b888489350b104c6af4e7a2ecbd903a4d)


### Day 4: April 30, 2025

**Progress**  
Edited the schema for payments and settlements, and added logic to calculate balances and generate settlements.  
Now the system can automatically determine who should pay how much to whom based on all users' payment history.

**Thoughts**  
I struggled with Pydantic—it was hard to follow how types were enforced in data passing throughout the code.

**Link**  
[walicaaa-backend GitHub commits](https://github.com/takuto-san/walicaaa-backend/commits/main/?since=2025-05-01&until=2025-05-01)


### Day 5: May 1, 2025

**Today's Progress**  
Worked on Assignment 3 of the "Deep Learning Fundamentals 2025" course by Matsuo Lab.  
Studied MLPs (Multi-Layer Perceptrons) and built a model for image recognition.

**Reflections**  
By implementing an AI model from scratch in a Python script in addition to the assignment, I was able to deepen my understanding.  
Used a publicly available Kaggle dataset of soccer player face images to train a model on the faces of eight players, including Messi and Ronaldo.


### Day 6: May 2, 2025

**Today's Progress**  
I started using Cisco Packet Tracer to study networking.
Since it was my first day, I worked through the tutorial sections.

**Reflections**  
Compared to studying theoretical concepts like the OSI reference model, I found it more engaging and less tedious to actually build networks on the screen.Hands-on learning made it easier and more enjoyable.


### Day 7: May 3, 2025

**Today's Progress**  
・Solved two problems from LeetCode’s Top Interview 150.
・Since my computer science tasks were starting to pile up, I organized and prioritized them.

**Reflections**  
・I want to continue studying computer science every day to strengthen my foundational skills, while sharing my progress using #100DaysOfCode.
・To start, I plan to work through each task based on how much time I actually have each day.
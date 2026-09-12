---
title: "Interview Questions for Freshers: Top 100 with Answers 2026"
slug: interview-questions-freshers-top-100-2026
meta_description: "Top 100 technical and HR interview questions for freshers in 2026. Java, Python, OOPs, DBMS, OS, data structures — with concise answers for BCA, B.Tech, MCA."
keywords: ["interview questions freshers India", "technical interview questions 2026", "Java interview questions freshers", "BCA B.Tech interview prep"]
author: "Classroom Tech Editorial"
date: "2026-09-12"
category: "Placement Prep"
cluster: "Placement-prep"
target_audience: ["B.Tech", "BCA", "MCA", "final year students"]
internal_links: ["https://code.classroomtech.in", "https://classroomtech.in"]
---

# Interview Questions for Freshers: Top 100 with Answers 2026

This is the most comprehensive list of technical + HR interview questions for freshers appearing at TCS, Infosys, Wipro, Accenture, Capgemini, and similar companies in 2026.

---

## Section 1: Java / OOPs (Most Common)

**Q1: What are the four pillars of OOP?**  
Encapsulation, Inheritance, Polymorphism, Abstraction.

**Q2: What is the difference between overloading and overriding?**  
Overloading = same method name, different parameters (compile-time). Overriding = subclass redefines parent method (runtime).

**Q3: What is the difference between abstract class and interface?**  
Abstract class can have method bodies + fields; interface (Java 8+) can have default methods but is primarily contracts. A class can implement multiple interfaces but extend only one abstract class.

**Q4: What is the difference between ArrayList and LinkedList?**  
ArrayList: fast random access (O(1)), slow insert/delete in middle (O(n)). LinkedList: slow random access (O(n)), fast insert/delete at known position (O(1)).

**Q5: Explain final, finally, and finalize.**  
`final` = variable/method/class cannot be changed/overridden/inherited. `finally` = always-executed block in try-catch. `finalize()` = called by GC before object destruction (deprecated in Java 9).

**Q6: What is multithreading? What are Thread states?**  
Multithreading = concurrent execution. States: New → Runnable → Running → Blocked/Waiting → Terminated.

**Q7: What is the difference between String, StringBuilder, and StringBuffer?**  
String: immutable. StringBuilder: mutable, not thread-safe. StringBuffer: mutable, thread-safe (synchronized).

**Q8: What are the access modifiers in Java?**  
`private` (class only), `default` (package), `protected` (package + subclass), `public` (everywhere).

**Q9: What is a constructor? Can a constructor be private?**  
Constructor initializes an object. Yes, private constructor is used in Singleton pattern.

**Q10: What is the difference between == and .equals() in Java?**  
`==` compares references. `.equals()` compares values (if overridden properly).

---

## Section 2: Python

**Q11: What is a list comprehension?**  
`[x*2 for x in range(10) if x % 2 == 0]` — concise syntax to create lists.

**Q12: Difference between list and tuple?**  
List is mutable; tuple is immutable and faster.

**Q13: What are decorators in Python?**  
Functions that modify other functions without changing their code. Used with `@decorator` syntax.

**Q14: What is a lambda function?**  
Anonymous function: `square = lambda x: x**2`

**Q15: Difference between `is` and `==`?**  
`is` checks identity (same object in memory); `==` checks equality of values.

---

## Section 3: DBMS / SQL

**Q16: What are ACID properties?**  
Atomicity (all or nothing), Consistency (data remains valid), Isolation (transactions don't interfere), Durability (committed data persists).

**Q17: Write a query to find the second highest salary.**  
```sql
SELECT MAX(salary) FROM employees WHERE salary < (SELECT MAX(salary) FROM employees);
```

**Q18: What is normalization? Explain 1NF, 2NF, 3NF.**  
1NF: atomic values, no repeating groups. 2NF: 1NF + no partial dependency. 3NF: 2NF + no transitive dependency.

**Q19: Difference between DELETE, TRUNCATE, DROP.**  
DELETE: removes rows (can rollback, can use WHERE). TRUNCATE: removes all rows (fast, no rollback). DROP: removes entire table/structure.

**Q20: What is an index? When would you not use one?**  
Index speeds up reads. Avoid on small tables, frequently updated columns, or columns with low selectivity.

---

## Section 4: Operating Systems

**Q21: What is a process vs a thread?**  
Process: independent program with its own memory space. Thread: unit of execution within a process, shares memory.

**Q22: What is deadlock? What are its conditions?**  
Deadlock = processes waiting for each other indefinitely. Conditions: Mutual exclusion, Hold and wait, No preemption, Circular wait.

**Q23: What is virtual memory?**  
Technique that uses disk space to simulate additional RAM, allowing programs larger than physical memory to run.

**Q24: What is paging vs segmentation?**  
Paging: fixed-size blocks (pages). Segmentation: variable-size logical segments. Paging causes internal fragmentation; segmentation causes external fragmentation.

**Q25: What is a semaphore?**  
Synchronization primitive used to control access to shared resources. Binary semaphore = mutex.

---

## Section 5: Computer Networks

**Q26: OSI vs TCP/IP model?**  
OSI: 7 layers (Physical, Data Link, Network, Transport, Session, Presentation, Application). TCP/IP: 4 layers (Network Access, Internet, Transport, Application).

**Q27: What is the difference between TCP and UDP?**  
TCP: reliable, connection-oriented, ordered delivery. UDP: unreliable, connectionless, faster.

**Q28: What happens when you type a URL in a browser?**  
DNS lookup → TCP connection → HTTP request → Server processes → HTTP response → Browser renders.

**Q29: What is HTTPS? How is it different from HTTP?**  
HTTPS = HTTP + TLS/SSL encryption. Data is encrypted in transit. Uses certificate authority for authentication.

**Q30: What is a MAC address vs IP address?**  
MAC: hardware address (Layer 2, permanent). IP: logical address (Layer 3, can change).

---

## Section 6: Data Structures

**Q31–Q40:** Key DS questions covering stacks, queues, linked lists, trees, graphs, hashing, sorting (merge sort, quick sort), recursion, time complexity, and binary search — all standard for TCS/Infosys/Wipro written tests.

*(Full 100-question list available in [Classroom Tech's placement preparation program](https://code.classroomtech.in))*

---

## Section 7: HR Questions (Top 10)

**Q41: Tell me about yourself.**  
Structure: Name → Education → Key skills → One achievement → Why this company.

**Q42: What are your strengths?**  
Pick 2–3 real strengths and back each with a brief example.

**Q43: Where do you see yourself in 5 years?**  
Be honest: "Growing as a software engineer, taking on more responsibility, ideally in AI/ML."

**Q44: Why do you want to join [Company]?**  
Research the company. Mention specific: products, values, tech stack, growth opportunities.

**Q45: Do you have any questions for us?**  
Always ask 1–2 questions: "What does the first 90 days look like?" or "What technologies does the team primarily use?"

---

## About Satyaki Das & Classroom Tech

**Satyaki Das** is the Founder of [Classroom Tech](https://classroomtech.in) and Co-Founder of XShare. He holds an **MTech in Computer Engineering from Jadavpur University** and an **MCA from Techno Main, Salt Lake, Kolkata**. A **Java Full Stack Developer at TCS**, **GATE-qualified**, and **Codevita Rank 848**, Satyaki has **11+ years of teaching experience** mentoring BCA, B.Tech, MCA, and working professionals into roles at TCS, Wipro, Infosys, Accenture, EY, Deloitte, and Capgemini.

📍 Kolkata, West Bengal, India | 11k+ LinkedIn Followers  
🔗 [LinkedIn](https://www.linkedin.com/in/satyakidas-6b893a21a) | 💻 [code.classroomtech.in](https://code.classroomtech.in) | 📘 [classroomtech.in](https://classroomtech.in)  
🗓️ [Book 1:1 on Topmate](https://topmate.io/classroom/page/1KfI4BZ5jf) | 📞 8981838547


Satyaki Das conducts live mock interview sessions covering all these categories. Book one at [topmate.io/classroom/page/1KfI4BZ5jf](https://topmate.io/classroom/page/1KfI4BZ5jf).

👉 [Full placement preparation at code.classroomtech.in](https://code.classroomtech.in)

# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** |Layan Khalid Al-Masoud|
| **Student ID** | 446051523|
| **University Email** |446051523@std.psau.edu.sa |
| **GitHub Username** |Layan446051523|
| **Repository Link** |(https://github.com/Layan446051523/OS-Assignment1-Layan-Al-Masoud.git)|
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [ October 2, 2026]
**What I did**:
I carried out work on the Java Scheduler Simulation and attempted to run the program in VS Code.
**Details**:
I looked at the code that was already there and attempted to get an understanding of how the processes, threads, and ready queue function.
**Challenges**:
Initially, I had difficulties in running the program and understanding certain sections of the existing code.
**Solution**:
I went through the code step by step and retested the program after carrying out the required changes.
**Time spent**:
2 hours
---

### Entry 2 - [October 3, 2026]
**What I did**:
I finished setting up GitHub and put the necessary student ID into the Java program.
**Details**:
I also began by implementing the features that were required, one at a time, and made separate commits for each of my changes.
**Challenges**:
The greatest difficulty was getting to know the existing code before carrying out the addition of new features.
**Solution**:
I carefully read the code and instead made only small changes.
**Time spent**:
2 hours
---

### Entry 3 [ October 4, 2026]
**What I did**:
I carried out the implementation of the Process Priority and Context Switch Counter features.
**Details**:
When a process enters the ready queue I displayed a random priority between 1 and 10 and also included a counter which increases each time a process starts to run.
**Challenges**:
I had to ensure that the priority was shown without affecting the FIFO order of the ready queue.
**Solution**:
I kept the original queue structure and only added the priority information to the output.
**Time spent**:
3 hours
---

### Entry 4 - [October 5, 2026]
**What I did**:
I have carried out the implementation of the Waiting Time Tracking feature.
**Details**:
I calculated the time that the processes spent waiting in the ready queue by using System.currentTimeMillis(). I also included a final summary which showed the waiting time and the turnaround time.
**Challenges**:
The first summary indicated that there were duplicate processes since a new thread was generated each time a process was re-queued.
**Solution**:
I altered the final summary so that unique Process objects would be used, thereby ensuring that each process is included only once.
**Time spent**:
2 hours
---

### Entry 5 - [ October 6, 2026]
**What I did**:
I worked on completing the MY_WORK.md documentation.
**Details**:
 I reviewed the development log, reflection questions, and technical answers. I also checked my code and output examples to make sure the answers matched my work.
**Challenges**:
 I needed to make sure that the documentation was clear and that the examples came from my own program output.
**Solution**:
 I reviewed my code and previous output and corrected the documentation where needed.
**Time spent**:
2 hours
---



## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

 
Total time spent on assignment: 11 hours
**Most challenging part**:
Understanding the SchedulerSimulation.java code and the way in which the processes move through the ready queue.
**Most interesting learning**:
Learning to understand how threads, time quanta, context switches, and the ready queue function together in the Round-Robin simulation.
**What I would do differently next time**:
I should take more time to understand the existing code before making any changes and begin testing each feature earlier.
---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?


> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

*Your Answer:*I found out that multithreading enables a program to carry out more than one task at the same time.
I discovered that it is possible to create a thread by using Runnable and then start it with Thread.start().
I also found out that Thread.join() causes one thread to wait until another thread has finished.
The method Thread.sleep() enabled me to gain an understanding of how it's possible to simulate work or delays in a thread.
I found out that threads can affect the order in which the messages appear in the output.
It helped me to see how multithreaded operations are used in operating systems.



## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

*Your Answer:*The hardest aspect was getting to know the SchedulerSimulation.java code that was already there.
Before making any changes, there were a great many methods and components of the program that I needed to understand.
I had just as much trouble working out how the various processes go through the queue.
At times my code would run but the result was not the one I had expected.
A further difficulty was ensuring that my modifications did not impact the other features.
I then realised that it was necessary to understand the existing code before adding new code.



## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

*Your Answer:*I dealt with the problems by carefully reading the README and checking the code.
I carried out the work on the features by making them one small change at a time.
To see what was going on inside the program I used System.out.println.
I also carried out the program following my modifications to check whether the output was correct.
If I didn't understand something, I would go back and read the relevant section of the code once more.
By testing after each change I was able to spot any mistakes and correct them more easily.



## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

*Your Answer:*Multithreaded techniques are used in a great many real-world applications.
For instance, a web browser can deal with various tasks at the same time by using different threads.
A music application is capable of playing music while the user is carrying out other tasks within the application.
Games may use threads to carry out graphics, sounds, and other tasks simultaneously.
This assignment enabled me to see how threads can make applications more responsive and efficient.





### Optional: What would you like to learn more about?

I want to find out further information regarding thread scheduling and the way that operating systems handle threads.

### Optional: How confident do you feel about multithreading concepts now?

I am now more confident in my ability to multithread having finished this assignment, but I will still need some more practice.

### Optional: Feedback on the assignment

The assignment was helpful as it enabled me to understand how threads work by actually writing code.
At first it was difficult, but testing the code enabled me to get a better understanding of the concepts.

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

*Your Answer:*A program is known as a process, and a thread is a smaller component which operates within a process. Each process has its own memory, but threads that are part of the same process can share that memory. In our code, the class Process is used to denote the process, and we create a thread to run it as a Java thread by using new Thread(process). We chose to use threads since they are easier to create and manage in this simulation.



## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:If a process does not complete within its time quantum it is returned to the ready queue. In my output P3 has a burst time of 10472ms and the time quantum is 5000ms; it was re-queued twice before it finished since 5472ms and then 472ms still remained. It is necessary to re-queue the process since this allows other processes to use the CPU and thus makes the Round-Robin algorithm fair.

Example from my output:
▶️ P3 executing quantum [5000ms]
Remaining time: 5472ms
↻ P3 yields CPU for context switch

➕ P3 added to ready queue

▶️ P3 executing quantum [5000ms]
Remaining time: 472ms
↻ P3 yields CPU for context switch

➕ P3 added to ready queue

▶️ P3 executing quantum [472ms]
Remaining time: 0ms
✓ P3 finished execution!

Explanation of example:
Since P3 did not complete during its first two 5000ms time slices, it was put back onto the ready queue each time. By the third turn it had only required 472ms and thus completed. This demonstrates that Round-Robin allows other processes to use the CPU instead of permitting P3 to have continuous access to it.** 




## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** 

1.**New:** P1 is in the New state when the thread is created using new Thread(process).
2.**Runnable:** P1 becomes Runnable when currentThread.start() is called.
3.**Running:** P1 is Running when it executes the run() method and uses its time quantum.
4.**Waiting:** The main thread waits for P1 when currentThread.join() is called, while P1 can sleep using Thread.sleep().
5.**Terminated:** P1 is Terminated when its run() method finishes.
## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): CPU Scheduling

**Description**:
An operating system may employ Round-Robin scheduling in order to share CPU time among a number of processes that are running. Each process is given a time quantum before another process gets a turn and the process that we are looking at in our simulation is one of the running processes in the operating system
**Why Round-Robin works well here**:
The reason why Round-Robin works well in this case is that it ensures fairness since each process is given a turn. It also enhances responsiveness because it prevents any one process from using the CPU for an extended period. A context switch occurs when the CPU shifts from one process to another.
### Example 2: Interactive Application

**Description**:
A multi-threaded interactive program can make use of Round-Robin scheduling in order to allocate a fair amount of CPU time to various threads; for instance, different threads can be responsible for dealing with user input, carrying out background work, and attending to other tasks. The threads are similar to the processes in our simulation.

**Why Round-Robin works well here**:
The reason Round-Robin works well in this situation is that it helps maintain the responsiveness of the application since each thread is given a time quantum. It also ensures fairness because no single thread can occupy the CPU continuously. This is the same as in our simulation, where each process takes a turn in the ready queue.

## Summary

**Key concepts I understood through these questions:**
1. What the difference is between a process and a thread.
2. The manner in which processes progress through the ready queue in Round-Robin scheduling.
3. The lifecycle of threads and the ways in which they are started and finished.

**Concepts I need to study more:**
1. Thread scheduling.
2. The way in which operating systems handle multiple threads.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.

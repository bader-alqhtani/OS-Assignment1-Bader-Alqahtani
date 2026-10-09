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
| **Full Name** | bader hamoud alqhtani |
| **Student ID** | 445050224 |
| **University Email** | 445050224@std.psau.edu.sa |
| **GitHub Username** | bader-alqhtani |
| **Repository Link** | https://github.com/bader-alqhtani/OS-Assignment1-Bader-Alqahtani |
 
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

### Entry 1 - [October 3 ,2026,7:30 AM]
**What I did**: Forked the repository, configured the project in VS Code, and set up student ID (445050224)

**Details**:
- I forked the starter repository and renamed it to my name.
- I cloned the repo to my PC and opened it in VS Code.
- I changed the student ID on line 150 in SchedulerSimulation.java to my actual ID (445050224).
- I ran the program to test it and make sure the baseline simulation works fine.

**Challenges**: At first, VS Code couldn't clone the repo because Git wasn't installed on my PC.

**Solution**: I downloaded and installed Git, restarted VS Code, and then cloned the project successfully.

**Time spent**: 50 minutes.

---

### Entry 2 - October 7, 2026 (05:00 AM)
**What I did**: Implemented feature 1 (process priority) and made sure it works

**Details**: I added a priority variable to the Process class with values from 1 to 10. I modified the constructor to take the priority and added a getPriority method. In main, I set up random priority generation when creating the processes, and I updated the print message in addProcessToQueue to show the priority in the console.

**Challenges**: The priority numbers were not showing in the terminal at first, and I was confused until I realized the file changes weren't saved and compiled yet. Also, I had to be careful not to mess up the FIFO queue order since the assignment said priority is only for display.

**Solution**: I checked where the console prints the message, saved the file properly, and ran it again from VS Code to verify that the priorities show up correctly.

**Time spent**: 4 hours

---

### Entry 3 - October 7, 2026 (11:20 PM)
**What I did**: Implemented feature 2, context switch counter, and checked the final count

**Details**: I added a static counter variable named contextSwitchCount inside the SchedulerSimulation class. Then inside the main scheduling while-loop, I incremented this counter right before currentThread.start each time a thread is dispatched. Finally, I added a print statement at the end of main after all processes finish to display the total context switches.

**Challenges**: Making sure the counter was placed in the correct scope so it increments on every single process execution rather than only when a process yields, and waiting for the full simulation to finish running to inspect the output at the very bottom of the terminal.

**Solution**: I declared the variable as static in the class, placed the increment right before thread execution in the scheduler loop, and verified the final printed number after all processes completed.

**Time spent**: 3 hours

---

### Entry 4 - October 9, 2026, (02:00 AM)
**What I did**: Implemented feature 3, waiting time and turnaround time tracking with a summary table

**Details**: I added creationTime and finishTime variables inside the Process class using System.currentTimeMillis. I updated run and runToCompletion to record when each process finishes executing. I added getter methods to calculate turnaround time and waiting time. In main, I created an array called allProcesses to store every process, and at the end of the simulation, I printed a summary table listing the process name, burst time, waiting time, and turnaround time.

**Challenges**: Making sure finishTime was recorded in both run and runToCompletion so no process was missed, and setting up the array size properly using numProcesses before the loop starts.

**Solution**: I recorded the finish timestamp in both methods right where the process marks completion, stored each created process by index in the array, and looped through it to print the table lines after the scheduler finished.

**Time spent**: 6 hours

---

### Entry 5 - October 9, 2026, 4:35 PM
**What I did**: Completed the Part B reflection and Part C technical questions in MY_WORK.md.

**Details**:
- Wrote answers for Part B about multithreading and Feature 3
- Answered Part C questions about thread states and thread vs process
- Added my console output for P5 to show how re-queueing works
- Wrote two examples for Round-Robin using desktop OS and game engines
- Filled out the summary section at the end

**Challenges**: Thinking of realistic and clear real-world examples for Round-Robin.   

**Solution**: Looked at how desktop apps share the CPU and how game engines update tasks during a frame.

**Time spent**: 3 hours

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [X hours]

**Most challenging part**:

**Most interesting learning**:

**What I would do differently next time**:

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

**Your Answer:** *(5-7 sentences)*

This assignment showed me how multithreading shares CPU time between tasks. I learned that our Process class implements Runnable to run on Java threads. The scheduler calls Thread.start() to begin, while currentThread.join() waits for the time slice to end. Using Thread.sleep() easily mimics work progress without stopping the program. I was surprised that threads share memory, which makes updating process data very simple.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

The hardest task was completing Feature 3 to calculate waiting and turnaround times. Saving finishTime was tricky because jobs exit in run() or inside runToCompletion(). Forgetting the timestamp in runToCompletion() would completely break the calculations for the last process. It was also difficult to store every process in an array without changing the queue order. Getting the console summary table properly aligned took several test runs.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I handled these issues by building one feature at a time instead of doing everything at once. When something went wrong, I used System.out.println to check variable values in the terminal. Reading the comments in SchedulerSimulation.java helped me understand how threads move through the queue. Testing the code inside VS Code let me see the live progress bars working properly. Checking my changes in the Source Control panel before committing kept the code clean.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading is very important in game engines like Godot to prevent lag. Godot uses separate background threads for physics, streaming audio, and loading maps. If it used one thread, the whole game would freeze during heavy file loading. Splitting work across threads gives every system quick CPU slices without stuttering. This assignment helped me see how time slicing keeps complex software smooth and responsive.

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

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

**Your Answer:** *(3-5 sentences)*

While a thread operates inside a process and shares memory with other threads, a process is an independent program with its own memory. Since true processes require too much memory and system overhead, we used threads in this case. Our code uses Thread thread = new Thread(process) inside addProcessToQueue() to wrap each job in a real Java thread. Our scheduler can readily share the queue and map in the same memory space by using threads. 

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

In Round-Robin, a process yields the CPU and is added back to the end of the ready queue if it does not complete within its time quantum. Because it prevents long processes from monopolizing the CPU and starving shorter tasks, this re-queueing behavior is crucial for fairness. Processes that had burst times longer than the time quantum in my simulation run had to wait several cycles to get their turn again. In my result, for instance, P5 ran for a quantum, yielded the CPU, then reentered the queue before being chosen to finish once more.

Example from my output:
```
▶ P5 executing quantum [3000ms] 
  ⚡ Quantum progress: [███████████████] 100%
  ⏸ P5 completed quantum 3000ms │ Overall progress: [██████████████░░░░░░] 70%
     Remaining time: 1240ms
  ↻ P5 yields CPU for context switch

  ➕ P5 (Priority: 2) added to ready queue │ Burst time: 4240ms

```

**Explanation of example:**
This sample shows P5 completing its 3000ms quantum with 1240ms of execution time remaining. It yields the CPU and is returned to the ready queue so waiting processes can get processor time.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**:  P1 enters this state when its Thread object is instantiated in addProcessToQueue() using Thread thread = new Thread(process).

2. **Runnable**: P1 moves to Runnable when the scheduler calls currentThread.start(), making it ready for CPU execution.

3. **Running**: P1 enters the Running state once the OS thread scheduler allocates CPU time to execute its run() method.

4. **Waiting**: P1 enters a timed waiting state inside run() during Thread.sleep(), while the main thread waits on currentThread.join().

5. **Terminated**: P1 reaches the Terminated state when its run() method finishes executing its remaining instructions.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): Desktop OS Interactive Process Scheduling

**Description**:
Round-Robin scheduling is used by contemporary desktop operating systems to distribute CPU time among several interactive user programs that are working simultaneously, such as a web browser, code editor, and terminal. Before the OS initiates a context switch to allow the next waiting application to run, each running application is given a brief time quantum to complete its present activities.

**Why Round-Robin works well here**:
Because no single background task or complex calculation can monopolize the CPU, Round-Robin guarantees responsiveness and fairness. The user interface is kept smooth and responsive to user input by constantly rotating small time slices across open applications.

### Example 2: Game Engine Subsystem Scheduling

**Description**:
Game engines in video game development run several background tasks across worker threads, including physics updates, NPC AI routines, and asset streaming. Instead of allowing one heavy task to run continuously, the engine uses Round-Robin scheduling to assign brief execution time slices to each system throughout each game frame.

**Why Round-Robin works well here**:
Round-Robin avoids stuttering and frame rate drops while offering predictability. The entire game render loop would lag if NPC pathfinding or physics calculations took over all CPU power. Gameplay is kept responsive and smooth by dividing execution evenly among small time slices.

## Summary

**Key concepts I understood through these questions:**
1. How Round-Robin shares CPU time fairly so long tasks do not freeze the system.
2. The difference between threads and processes in memory usage and overhead.
3. How Java thread states change using start(), sleep(), and join().

**Concepts I need to study more:**
1. How game engines split background tasks across threads to prevent FPS drops.
2. How to safely share game data between threads without breaking gameplay logic.

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

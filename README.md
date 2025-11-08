# Interactive Lab Report Assistant

### A submission for the "Build with Perplexity Comet" Hackathon by Aniket Mehra.

**Elevator Pitch:** Turning hours of student work into a task of just a few minutes.

---

## 🎥 Video Demonstration

Click the image below to watch the full project demo on YouTube.

**Direct Link:** (https://youtu.be/p-AjP0wCTvo)

---

## 💡 The Problem

Students spend countless hours on the tedious manual work of writing lab reports. This workflow automates that entire process using the power of Perplexity Comet.

## ✅ The Solution

This project uses a single, human-friendly prompt to command an AI agent to research, calculate, and write a complete, high-quality lab report from a student's raw data.

---

## 🚀 The Master Prompt (The "Source Code")

This is the engine of the entire project. It's the exact prompt used in the video demonstration.

```text
Hi, can you please help me write a full lab report? Here are all the details.

1. The Topic of the Lab:
 A simple pendulum experiment to calculate gravity (g). 

2. My Raw Data:
(Just describe your data in simple sentences)
[ - For a pendulum length of 0.5 meters, it took 14.2 seconds for 10 swings. ]
[ - For a pendulum length of 1.0 meter, it took 20.1 seconds for 10 swings. ]
[ - For a 1.5-meter pendulum, it took 24.6 seconds for 10 swings. ]

3. The Main Formula We Used:
[ T = 2π√(L/g) ]

What I Need You to Write:

Based on the information above, please write a complete report for me that includes these five sections in order:
1.  Introduction: Explain the science behind the topic.
2.  Procedure: List the likely steps I took in the lab.
3.  Results: Do all the math and put everything in a clean data table.
4.  Conclusion: Summarize the final result and what it means.
5.  Error Analysis: List three common sources of error for this experiment.

Please write it all out as one single piece of text that I can easily copy and paste. Thanks so much!
```

🛠️ Built With

Perplexity Comet

Prompt Engineering

No-Code

Google Docs

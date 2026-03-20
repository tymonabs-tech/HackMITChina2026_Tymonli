# HackMITChina2026_Tymonli
Tymonli's HackMITChina2026 team Pro Gpa Planner tool
# 🎯 GPA Pro Planner

A lightweight, browser-based tool that not only calculates your current GPA, but also generates an explainable plan to help you achieve your target GPA across multiple subjects.

---

## 🚀 Overview

GPA Pro Planner goes beyond traditional GPA calculators by answering a more important question:

👉 *"What should I aim for next?"*

It provides real-time GPA calculation and generates a clear, goal-oriented academic plan based on user inputs, even when data is incomplete or grading systems vary.

---

## ✨ Key Features

- 📊 **Real-time GPA Calculation**  
  Automatically computes overall GPA using a weighted average formula

- 🎯 **Target GPA Planning**  
  Generates per-subject recommended GPAs to reach your goal

- ⚠️ **Feasibility Analysis**  
  Detects unrealistic targets and provides clear feedback

- 📱 **Mobile-Friendly UI**  
  Clean and responsive interface for easy access on any device

- 🧠 **Explainable Algorithm**  
  Includes an "Algorithm Explanation" page for transparency

- 💾 **Local Data Persistence**  
  Save and reload your academic data using IndexedDB

- 🔁 **Batch Editing with Undo**  
  Safely update credits with reversible operations

---

## 🧩 How It Works

1. Select your GPA scale (e.g., 4.0 / 5.0)
2. Input subjects with:
   - Current GPA
   - Credits (optional)
   - Difficulty
3. Set your target GPA
4. Get:
   - Recommended GPA per subject
   - Feasibility feedback
   - Clear, structured results

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Routing:** Hash-based SPA navigation  
- **Storage:** IndexedDB  
- **Testing:** Node.js built-in test runner  

---

## ⚙️ Algorithm Design

The planning logic is implemented as a **pure function**, ensuring:

- High testability  
- Stable outputs  
- Easy future extension  

### Strategy:
- Uses a **greedy allocation approach**
- Guided by an **efficiency score**
- Applies a **diminishing returns penalty**

👉 This prevents unrealistic concentration of improvement in a single subject.

---

## 📦 Project Structure


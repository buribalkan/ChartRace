# 🎬 How to Make a Live Chart Race in Pure SVG (No Libraries!)

📊 **Dynamic data visualizations** are no longer reserved for massive frameworks. 
**fully animated chart race** — entirely in **HTML, SVG, and vanilla JavaScript** — with cool features like live rankings, emojis, tooltips, flashing leaders, and more.

> ✅ No frameworks 
> ✅ No canvas 
> ✅ 100% SVG + JavaScript

---

## 🚀 What You’ll Build

A real-time animated **bar chart race** where:

- Each bar represents a country’s export score 📦 
- Bars **move, grow, and reorder** over time 🔄 
- A live **leaderboard** ranks countries by value 🏆 
- The current leader **glows gold** 🔥 
- Bars **change color dynamically** 🎨 
- You can **pause/resume** the race ⏯️ 
- Hovering shows **tooltips** with extra info 🧠 

> Let’s go!

---

## 🔧 Step-by-Step Guide

### ✅ Step 1: Set Up HTML & SVG

We create a chart area using `<svg>` and populate it with:
- a `<rect>` for each bar
- a `<text>` for the country name
- a `<text>` for the score
- a `<image>` for flags/emojis

```html
<svg width="740" height="260" id="chart"></svg>

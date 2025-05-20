# My Weekly Walking Profile Analysis
## Overview

![Image alt](https://www.une.edu.au/__data/assets/image/0016/261106/nature-walksm.jpg)


> "In every walk with nature, one receives far more than he seeks." — John Mulr

Here is an ovrview of the **number of steps** I walked each day over the course of a week and compares the data:
- *Over time* (daily progress)
- *With friends* (average steps among peers)

~~Purely for fun~~
---

## Daily Step Count

| Day       | My Steps | Friends' Avg Steps |
|-----------|----------|--------------------|
| Monday    | 6,120    | 7,500              |
| Tuesday   | 7,880    | 7,230              |
| Wednesday | 10,200   | 8,150              |
| Thursday  | 5,300    | 6,700              |
| Friday    | 12,000   | 9,200              |
| Saturday  | 8,600    | 10,100             |
| Sunday    | 9,400    | 9,800              |


<!-- Data is 95% accurate -->
---

## Insights

### Progress Over Time

- I showed **steady improvement** from Monday through Friday.
- Thursday was a *low-performance* day due to bad weather.
- Friday had a *peak performance*, thanks to an outdoor group walk.

### Comparison with Friends

1. Overall, I was **below average** on 3 days and **above average** on 4 days. 
2. I'm always the step leader — **Data says otherwise**.

---

## Code Snapshot

The following code was used to compute average steps per day:

```rst 
def avg_steps():
    days = ["Mon", "Tue", "Wed", "Thu", "Fri", "Sat", "Sun"]
    my_steps = [6120, 7880, 10200, 5300, 12000, 8600, 9400]
    avg_steps = sum(my_steps) / len(my_steps)
    print(f"Average steps this week: {avg_steps}")

```
The average steps this week is `8431.43`
---
[More Reading](https://www.une.edu.au/about-une/news-and-events/stories/2019/03/walking-in-nature-is-good-for-head-heart-and-soul)

To sum up:
- [x] Upload and display steps data

- [ ] Analyse the data for trends
<!-- This webpage will be upgraded later -->
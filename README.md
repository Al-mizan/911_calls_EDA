# 911 Calls EDA | Kaggle Notebook

This project explores and visualizes a real dataset of 911 emergency calls from Montgomery County, Pennsylvania. The goal is to uncover patterns in emergency types, geographical distribution, and call volumes using powerful Python libraries.

---

## Dataset

The dataset is available from [Kaggle - 911 Calls](https://www.kaggle.com/datasets/mchirico/montcoalert).  
It contains over 50,000 emergency calls made to 911, with fields like:

- `lat` and `lng`: Location of the call
- `zip`: ZIP code of the incident
- `title`: Type of emergency
- `timeStamp`: Time the call was placed
- `twp`: Township
- `desc`: Description of the call

---

## Key EDA Highlights

- Identified top ZIP codes and townships with the most 911 calls.
- Extracted call Reasons (EMS, Fire, Traffic) and visualized their frequency.
- Analyzed call volume trends by hour, day, and month using time-based features.
- Created heatmaps showing call density by hour vs. weekday and month vs. weekday.
- Uncovered temporal and spatial patterns in emergency response behavior.

---

## How to Run (on Kaggle)

1. Go to the [Kaggle notebook](https://www.kaggle.com/code/mdalmizan/911-calls-eda)
2. Click **"Copy and Edit"** to run your own version
3. All dependencies are pre-installed on Kaggle
4. The dataset is directly accessible within the notebook environment

---
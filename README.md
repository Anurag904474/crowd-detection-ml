# 🧠 Crowd Detection Using YOLOv8

This project detects **crowd events** in a video using a pre-trained **YOLOv8** model and Python. A *crowd* is defined as **three or more persons standing close together for at least 10 consecutive frames**. The results are logged into a CSV file.

---

## 📌 Features

- Detects persons using **YOLOv8** object detection.
- Identifies when 3 or more people are **close together**.
- Tracks if the group remains for **10+ frames**.
- Logs detected crowd events with **frame number** and **person count**.
- Outputs to a CSV: `crowd_detection_log.csv`.

---

## 📁 Project Structure


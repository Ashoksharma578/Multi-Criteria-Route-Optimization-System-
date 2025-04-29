# 🛣️ Multi-Criteria Route Optimization System

An intelligent Python-based route planning system that helps users find optimal travel routes based on multiple factors such as cost, time, satisfaction, fuel usage, tolls, traffic, and road quality. Designed as part of a DAA course project to demonstrate real-world applications of graph algorithms.

## 🚀 Features

- 📍 User-defined start and destination points
- ⚖️ Multi-criteria optimization: cost, time, satisfaction
- 📈 Weighted graph modeling of route networks
- 🧠 Uses **Dijkstra’s Algorithm** and **Bellman-Ford Algorithm**
- 📊 Realistic scoring system for traffic, road quality, and tolls
- 🧪 CLI-based interaction for quick testing and prototyping

## 🛠️ Tech Stack

- **Language**: Python
- **Concepts Used**: Graphs, Dijkstra’s algorithm, Bellman-Ford algorithm, Multi-Criteria Decision Making
- **Libraries**: `sys`, `heapq`

## 📂 Folder Structure

Multi-Criteria-Route-Optimization-System/ ├── main.py ├── graph_data.py ├── readme_assets/ │ └── screenshot.png (optional) └── README.md

bash
Copy
Edit

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Ashoksharma578/Multi-Criteria-Route-Optimization-System-.git
   cd Multi-Criteria-Route-Optimization-System-
Run the program:

bash
Copy
Edit
python main.py
Follow on-screen instructions to:

Enter source and destination

Choose your optimization criteria

View the best route and details

⚙️ Optimization Criteria Details

Criteria	Factors Considered
Cost	Fuel cost, tolls
Time	Road distance, traffic rating
Satisfaction	Aesthetic roads, smoothness, traffic, scenery
📌 Sample Output
yaml
Copy
Edit
Start: Delhi
Destination: Agra
Optimization: Cost
Best Route: Delhi → Mathura → Agra
Total Cost: ₹350 | Estimated Time: 3.5 hours | Satisfaction: 8.2/10
🎯 Learning Outcomes
Implementing and customizing classic graph algorithms

Designing CLI tools for real-world problems

Applying weights for subjective factors like "satisfaction"

Balancing optimization trade-offs

📸 Screenshot

(Optional: Replace with your own visual)

🔮 Future Improvements
Add GUI using Tkinter or React + Flask

Live traffic data integration via APIs

Export routes as PDF or map preview

Route animation or visualization

📄 License
This project is licensed under the MIT License.

Developed by Ashok Sharma with ♥

yaml
Copy
Edit

---

### ✅ To Use:
Save this content as `README.md` in your project folder and push it to GitHub using:

```bash
git add README.md
git commit -m "Add project README"
git push

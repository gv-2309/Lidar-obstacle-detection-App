# LIDAR Obstacle Detection App

**Team-Mind_Mesh**  
Developers: Amrutha D, Vishnu V  
Institution: REVA University, Bangalore

## 🔴 Live Demo  
https://lidar-obstacle-detection-app.streamlit.app/

## 🧠 GitHub Repository  
https://github.com/gv-2309/Lidar-obstacle-detection-App

---

## 🚩 Problem Statement  
[Robotics] Problem-1.1: Obstacle Detection using LIDAR Data of a Robot 

---

## 💡 Features

- Upload your own LIDAR CSV file or choose from built-in test cases
- Detects obstacles within a **10-meter radius** from origin (0,0,0)
- Categorizes detected points based on distance:
  - **High Danger**: < 3m
  - **Medium Danger**: 3–6m
  - **Low Danger**: 6–10m
- Clusters nearby obstacle points using **DBSCAN**
- Displays an interactive 2D scatter plot showing all points and danger zones
- Simple, interactive interface powered by Streamlit

---



---

## 📦 Requirements

Install the required Python libraries:

```bash
pip install -r requirements.txt
💻 How to Run the App Locally on VS Code
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/gv-2309/Lidar-obstacle-detection-App
cd lidar-obstacle-detection-app
2. Create a Virtual Environment (Recommended)
bash
Copy
Edit
python -m venv venv

# Activate it:
# On Windows
venv\Scripts\activate

# On Mac/Linux
source venv/bin/activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
Also install system dependencies (Linux):

bash
Copy
Edit
sudo apt-get install libgl1-mesa-glx
4. Ensure Folder Structure
Make sure your project files look like this:

css
Copy
Edit
lidar-obstacle-detection-app/
├── main.py
├── requirements.txt
├── packages.txt
├── lidar_test_files/
│   ├── test_case_1.csv
│   └── test_case_2.csv
5. Run the Streamlit App
bash
Copy
Edit
streamlit run main.py
6. Open in Browser
Go to:
http://localhost:8501

📁 Sample Input Format
CSV file must contain 3D point cloud data (no headers):

python-repl
Copy
Edit
X, Y, Z
10, 0, 0
1, 1, 0
...
🎥 Demo Video
Watch the demo here:
https://tinyurl.com/hackotsav-2k25

📞 Contact
For queries or collaboration, reach out at:
gvs.vishnuv@email.com | amruthadandigimath@gmail.com

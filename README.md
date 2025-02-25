# 📊 Interactive Page Replacement Algorithm Simulator

## 🚀 About the Project
This *Python GUI application* implements three page replacement algorithms with dynamic visualizations:
- *FIFO (First In First Out)*
- *LRU (Least Recently Used)*
- *Optimal Page Replacement*

Experience real-time simulations, compare algorithms, and visualize page faults through interactive charts!

---

## ✨ Key Features
✅ *Interactive GUI* built with Tkinter  
✅ *Real-time simulation* of FIFO, LRU, and Optimal algorithms  
✅ *Side-by-side algorithm comparison* with bar charts  
✅ *Animated step-by-step visualization* of frame changes  
✅ *Fault-over-time tracking* for all algorithms  
✅ Detailed *step-by-step execution traces*  
✅ Responsive design with *clean visual aesthetics*

---

## 🛠️ Installation & Usage

### 1️⃣ Clone the Repository
bash
git clone https://github.com/mansityagi01/PageReplacementSimulator.git
cd PageReplacementSimulator


### 2️⃣ Install Python Dependencies
bash
pip install matplotlib


### 3️⃣ Run the Application
bash
python3 simulator_gui.py  # Linux/macOS
python simulator_gui.py   # Windows


---

## 🖥️ GUI Walkthrough
![GUI Demo](https://via.placeholder.com/800x500.png?text=GUI+Demo+with+Algorithms+Comparison)

### 🎮 Interface Components:
1. *Input Section*: 
   - Page reference string (e.g., 1 2 3 4 1 2)
   - Number of frames selector
   - Algorithm dropdown (FIFO/LRU/Optimal)

2. *Control Buttons*:
   - 🟢 *Simulate*: Run selected algorithm
   - 🔵 *Compare All*: Generate comparison chart
   - 🔴 *Clear*: Reset all inputs

3. *Output Section*:
   - 📜 *Step-by-step execution log*
   - 📈 *Live animation* of frame changes
   - 📊 *Comparative bar charts* of page faults

---

## 📊 Visualization Samples

### 1️⃣ Algorithm Comparison Chart
![Comparison Chart](https://via.placeholder.com/600x300.png?text=FIFO+vs+LRU+vs+Optimal+Faults+Comparison)

### 2️⃣ Real-time Frame Animation
![Frame Animation](https://via.placeholder.com/600x200.png?text=Animated+Frame+Updates+Per+Step)

### 3️⃣ Fault Timeline Analysis
![Fault Timeline](https://via.placeholder.com/600x200.png?text=Fault+Occurrence+Over+Time)

---

## 🧠 Technical Implementation
### Core Components:
- *PageReplacementSimulator Class*: Manages GUI state and simulations
- *Algorithm Implementations*:
  python
  def fifo(self, page_string, frame_size):
      # FIFO implementation logic
      
  def lru(self, page_string, frame_size):
      # LRU implementation using recent list
      
  def optimal(self, page_string, frame_size):
      # Optimal implementation with future lookup
  
- *Matplotlib Integration*:
  - Dynamic chart updates using FuncAnimation
  - Dual-axis plots for comparison and trend analysis

---


## 👩💻 Author-  
*Arshi Bansal  
[![GitHub](https://img.shields.io/badge/GitHub-Profile-blue?logo=github)](https://github.com/ArshiBansal)  
💡 *Pro Tip*: Use prime number sequences (e.g., 2 3 5 7 11) for interesting fault patterns!

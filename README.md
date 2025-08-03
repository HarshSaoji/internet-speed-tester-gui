
# 🚀 Internet Speed Tester GUI using Python

A sleek and user-friendly GUI Internet Speed Tester built using Python’s Tkinter and speedtest-cli. It quickly measures download and upload speeds, along with ping, all within a simple graphical interface. Ideal for users who want a lightweight, no-code solution to check their internet performance effortlessly.


---

## 📸 Preview

> *(![result](https://github.com/user-attachments/assets/cdaf37b6-c2f5-4aea-9a80-3a8dc24526c4))*

---

## 🧰 Technologies Used

- **Python 3.x**
- **Tkinter** – for GUI
- **speedtest-cli** – to perform speed tests
- **Jupyter Notebook** – for development interface

---

## ✨ Features

- ✅ Real-time testing of **Download** and **Upload** speeds
- ✅ Displays **Ping (latency)**
- ✅ Built with a user-friendly **Tkinter GUI**
- ✅ Customizable window with optional `.ico` icon
- ✅ Lightweight and beginner-friendly

---

## 📦 Installation

Follow the steps below to set up and run the project on your local machine.

### 1. Clone the repository

```bash
git clone https://github.com/your-username/internet-speed-tester-gui.git
cd internet-speed-tester-gui
```

### 2. Install dependencies

Install the `speedtest-cli` package:

```bash
pip install speedtest-cli
```

### 3. Run the project

You can either:
- Run the notebook directly in **Jupyter**:  
  Open `005_Test_Internet_Speed.ipynb` and run all cells

**OR**

- Convert to a `.py` file and run from terminal:

```bash
python speed_tester_gui.py
```

> 📌 **Note**: If you get a `TclError` about `"speed.ico"` not found, either make sure the file is in the same directory or comment out the `root.iconbitmap('speed.ico')` line.

---

## 📁 Project Structure

```
internet-speed-tester-gui/
├── Test_Internet_Speed.ipynb       # Main Jupyter Notebook
├── speed.ico                       # (Optional) Icon for GUI window
├── screenshot.png                  # (Optional) GUI preview image
├── README.md                       # Project documentation
└── .gitignore                      # File exclusions
```

---

## 🧠 How It Works

- The app uses the `speedtest` Python package to measure:
  - Download speed
  - Upload speed
  - Ping (latency)
- The GUI displays these values in a simple window after pressing the **"Check Speed"** button.
- The background is styled for a clean and modern look using `Tkinter`.

---

## 💡 Customization Tips

- Replace `speed.ico` with your own `.ico` file to personalize the window icon.
- Convert the `.ipynb` notebook to `.py` using:

```bash
jupyter nbconvert --to script 005_Test_Internet_Speed.ipynb
```

---

## 🔧 Troubleshooting

| Issue | Solution |
|-------|----------|
| `TclError: bitmap "speed.ico" not defined` | Ensure the `speed.ico` file is present or comment out the line `root.iconbitmap('speed.ico')`. |
| GUI not launching | Make sure you're using a Python version with `Tkinter` installed. Try running with `pythonw` on Windows. |
| `ModuleNotFoundError: No module named 'speedtest'` | Run `pip install speedtest-cli` to install the required module. |

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

- ⭐ Star the repository
- 🐞 Report bugs or issues
- 📥 Submit a pull request to add new features or improvements

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Harsh Saoji**  
 B.Tech CSE (Data Science) 

> For queries or collaborations, feel free to connect on [LinkedIn](https://linkedin.com) or raise an issue on GitHub.

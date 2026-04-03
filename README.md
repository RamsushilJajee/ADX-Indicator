# 📈 ADX-Indicator Analysis Tool

A professional Django-based web application designed to calculate and visualize the **Average Directional Movement Index (ADX)**. This tool helps traders and analysts quantify trend strength regardless of price direction.

---

## 🧐 Understanding ADX
The **Average Directional Index (ADX)** is a technical indicator used to quantify trend strength. It is non-directional, meaning it registers trend strength whether the price is moving up or down.

* **Uptrend (+DMI > -DMI):** Prices are moving up; ADX measures the strength of the bullish trend.
* **Downtrend (-DMI > +DMI):** Prices are moving down; ADX measures the strength of the bearish trend.

---

## 🛠 Prerequisites
Ensure you have the following installed to maintain project compatibility:

| Requirement | Version |
| :--- | :--- |
| **Python** | 3.9.0 |
| **Django** | 4.1 |
| **Data Libraries** | Pandas, Numpy |
| **Visualization** | Matplotlib |

---

## 🚀 Installation & Setup

### Environment Configuration
First, download the `myproject` folder. Open your terminal or command prompt in the `myproject` directory and run the following:

```
# Create the virtual environment
virtualenv venv

# Activate the environment
# On macOS/Linux:
source venv/bin/activate
# On Windows:
venv\Scripts\activate
```


### 📦 Install Dependencies
With the virtual environment activated, install the necessary packages using pip:

```
pip install django pandas numpy matplotlib
```

### ⚡ Launch the Application
Run the Django development server using the following command:

```
python manage.py runserver
```

Open your web browser and navigate to: http://127.0.0.1:8000/

### 🖥 User Guide
1. File Naming: In the first field, type the name you wish to assign to your output file.
2. Upload Data: Select your data file using the file upload field.
3. Execute: Click the Submit button. A new window will pop up displaying the generated ADX Plot.
4. Download: Once you close the plot window, a download link will appear on the main page, allowing you to save the processed solution.

### 🛑 Project Shutdown
To stop the server, press `Ctrl+C` in your terminal. To exit the virtual environment and return to your global Python settings, simply run:

```
deactivate
```

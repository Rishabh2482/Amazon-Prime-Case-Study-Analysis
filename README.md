# 🎬 Amazon Prime Video Data Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on the Amazon Prime Video dataset to uncover trends in content strategy, audience preferences, and global distribution. 

By analyzing over **9,000 titles** and **124,000 cast members**, this project answers critical business questions such as:
* **Content Strategy:** Is Amazon focusing more on Movies or TV Shows?
* **Global Reach:** Which countries produce the most content?
* **Quality vs. Quantity:** How does the volume of content correlate with IMDb/TMDB ratings?
* **Talent Analysis:** Who are the most prolific actors and directors on the platform?

## 📂 Dataset Description
The analysis uses two linked datasets:
1.  **`titles.csv`**: Contains metadata for 9,000+ titles (Title, Type, Release Year, Rating, Runtime, Genres).
2.  **`credits.csv`**: Contains cast and crew information (Actor/Director Names, Characters, Roles).

> **Note:** These files must be in the same directory as the notebook for the code to run.

## 🛠️ Libraries Used
* **Pandas**: Data manipulation and merging.
* **NumPy**: Efficient numerical operations.
* **Matplotlib & Seaborn**: Data visualization and storytelling.

---

## 🚀 How to Run on Google Colab

Follow these steps to run this project directly in your browser using Google Colab.

### Step 1: Get the Project Files
You need a local copy of the data and the notebook first.
1.  Click the **Code** button (green) on this repository.
2.  Select **Download ZIP**.
3.  Extract the ZIP file to a folder on your computer.

### Step 2: Open Google Colab
1.  Go to [Google Colab](https://colab.research.google.com/).
2.  Click **File** > **Upload Notebook**.
3.  Select the `.ipynb` file (Jupyter Notebook) you just downloaded from this repository.

### Step 3: Upload the Data (Crucial Step!)
For the code to read the data, you must upload the CSV files to the Colab session.
1.  On the left sidebar of Colab, click the **Folder icon** (📁).
2.  Click the **Upload icon** (an arrow pointing up into a file).
3.  Select **both** `titles.csv` and `credits.csv` from your extracted folder.
4.  Wait for the upload to finish.

### Step 4: Run the Analysis
1.  Click **Runtime** > **Run all** (or press `Ctrl+F9`).
2.  The notebook will process the data and generate the visualizations.

---

## 📊 Key Insights
* **Content Mix:** Analysis of the ratio between Movies and TV Series.
* **Genre Dominance:** A breakdown of the top 10 genres (e.g., Drama, Comedy).
* **Production Hotspots:** A map of the top content-producing countries.
* **Rating Trends:** An investigation into whether newer content is getting better or worse ratings over time.

## 👤 Author
Rishabh Kumar Chauhan  
*Connect with me on [LinkedIn Profile Link](https://www.linkedin.com/in/-91rishabh-chauhan/)*



# Flight Price Prediction - EDA & Feature Engineering  

## 📌 Project Overview  
This project aims to predict flight ticket prices based on various factors such as airline, departure time, duration, and seat class. The dataset is analyzed using **Exploratory Data Analysis (EDA)** and **Feature Engineering** to extract meaningful insights and improve model performance.

---

## 📂 Dataset Description  
The dataset contains flight details including airlines, departure time, stops, and ticket prices. The cleaned dataset features are explained below:

### ✈ Features:  
1. **Airline** - Categorical feature indicating the airline company (6 unique airlines).  
2. **Flight** - Categorical feature storing flight information.  
3. **Source City** - City from which the flight takes off (6 unique cities).  
4. **Departure Time** - Derived categorical feature representing time bins for departure (6 unique labels).  
5. **Stops** - Categorical feature representing the number of stops between source and destination (3 values).  
6. **Arrival Time** - Derived categorical feature representing arrival time bins (6 unique labels).  
7. **Destination City** - City where the flight lands (6 unique cities).  
8. **Class** - Categorical feature indicating seat class (Business or Economy).  
9. **Duration** - Continuous feature displaying total travel time in hours.  
10. **Days Left** - Derived feature representing days left until departure.  
11. **Price** - Target variable representing ticket price.

---

## 🔎 Exploratory Data Analysis (EDA)  
- **Handling missing values** (if any).  
- **Distribution analysis** of features.  
- **Correlation analysis** to understand feature dependencies.  
- **Visualization of price variations** with respect to different factors.

---

## 🔧 Feature Engineering  
- **Encoding categorical features** using One-Hot Encoding.  
- **Creating time-based bins** for better modeling.  
- **Transforming numerical features** like duration and days left.  

---

## 🛠 Tech Stack  
- **Python**  
- **Pandas & NumPy** (Data Manipulation)  
- **Matplotlib & Seaborn** (Data Visualization)  
- **Scikit-Learn** (Preprocessing & Encoding)


---

## 🚀 Getting Started  

### 🔹 Install Dependencies  
```bash
pip install -r requirements.txt
```

### 🔹 Run Jupyter Notebook  
```bash
jupyter notebook
```
Open the **EDA & Feature Engineering Notebook** and execute the cells.

---

## 📊 Results & Insights  
- Ticket prices vary significantly based on **airline, departure time, and seat class**.  
- **Non-stop flights are more expensive** compared to those with layovers.  
- Business-class tickets have a **higher price range** than economy-class tickets.  
- **Booking in advance (Days Left feature) reduces ticket prices** significantly.


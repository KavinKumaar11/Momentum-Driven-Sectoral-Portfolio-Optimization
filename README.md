# 📈 Momentum-Driven Sectoral Portfolio Optimization

This project demonstrates a momentum-based investment strategy applied across three equity sectors using historical price data and optimization modeling. By combining financial analytics with mathematical optimization, it simulates intelligent capital allocation decisions for retail or institutional investors.

---

## 🚀 Project Highlights

- **Data Source:** Historical equity prices from Yahoo Finance (`yfinance`)
- **Sectors Analyzed:** Technology, Consumer Discretionary, and Industrials
- **Stock Filtering:** Relative strength and normalized price movements to select momentum stocks
- **Optimization Framework:** Pyomo + IDAES for constrained capital allocation
- **Objective:** Maximize returns while satisfying diversification and budget constraints

---

## 📊 Methodology

1. **Data Collection:**  
   Retrieved daily adjusted closing prices for top sector stocks using `yfinance`.

2. **Exploratory Data Analysis (EDA):**  
   - Time-series plots to visually compare stock growth  
   - Normalized pricing for momentum comparison  
   - Sector-based stock segmentation

3. **Momentum Filtering:**  
   - Selected top 2 momentum stocks per sector  
   - Momentum calculated using recent price growth trends

4. **Portfolio Optimization:**  
   - Built a linear programming model using Pyomo  
   - Constraints: total capital ≤ 1, diversification across sectors, non-negative weights  
   - Solver: IDAES with extension support

5. **Output:**  
   - Optimal allocation weights for each selected stock  
   - Visual representation of final portfolio composition

---

## 🛠 Tools & Libraries

- Python 3  
- Pandas  
- Matplotlib  
- yfinance  
- Pyomo  
- IDAES-PSE  

---

## 📁 File Structure

- `Momentum-Driven-Sectoral-Portfolio-Optimization.ipynb` – Full working notebook  
- `.pyomo` & `.idaes` – Optimization and solver backends (installed via pip)

---

## 💡 Skills Demonstrated

- Sectoral momentum analysis  
- Financial time-series visualization  
- Mathematical modeling with Pyomo  
- Portfolio theory application  
- Optimization under constraints  
- Practical use of Yahoo Finance API

---

## 👤 Author

**Kavin Kumaar**  
Graduate Student – MS in Business Analytics & Project Management  
University of Connecticut  
[LinkedIn](https://www.linkedin.com/in/rtkavinkumaar22/) | [Portfolio](https://github.com/KavinKumaar11) | [Email](mailto:rtkavinkumaar112219@gmail.com)

---

## 📜 License

This project is released under the MIT License.

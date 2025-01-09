# **Stage-Analysis Trading Strategy**

This strategy is **inspired by Stan Weinstein's Stage Analysis Trading Strategy**.

---

## **Built With**
- **Python**
- Python libraries: **Pandas**, **Numpy**, and **matplotlib.pyplot**
- **Yahoo Finance** API to fetch stock data

---

## **The Actual Strategy**

This strategy evaluates **three main indicators** when deciding whether to **short** or **long** a stock:  
1. **Trading Volume**  
2. **Price Action**  
3. **Stages**

### **Trading Volume**
- Checks whether the **volume is above average**, indicating a **strong move**.

### **Price Action**
- Determines if the stock's price is **above the 100-Day Moving Average** or **below the 100-Day Moving Average**.

### **Stage Analysis**
- Assigns a **stage** to the stock every day.  
- Based on the stock's **price action**, the stock is categorized into **one of four stages**:

  - **Stage 1: Consolidation**  
  - **Stage 2: Advancing Phase/Uptrend**  
  - **Stage 3: Distribution Phase/Topping**  
  - **Stage 4: Declining Phase/Downtrend**  

---

## **Trading Rules**

- **LONG**:  
  Enter a long position if:  
  - **Volume confirmation** exists,  
  - The price is **above the 100-Day Moving Average**, and  
  - The stock is in **Stage 1** or **Stage 2**.

- **SHORT**:  
  Enter a short position if:  
  - **Volume confirmation** exists,  
  - The price is **below the 100-Day Moving Average**, and  
  - The stock is in **Stage 3** or **Stage 4**.

---

### 📈 **Key Advantages of the Strategy**:
- Clear, rules-based approach.
- Incorporates technical indicators for **objective decision-making**.
- Adaptable to multiple stocks and market conditions.

---

Feel free to contribute, open issues, or give suggestions to improve the strategy! 🚀

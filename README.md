
# Smart Life Assistant

## 📌 Project Overview
Smart Life Assistant is a JavaScript-based console/prompt application that performs 4 useful daily life tasks using **conditional statements**, **range-based logic**, and **string comparisons**.

---

## 🧩 Tasks

### 1. 🏃‍♂️ Fitness Suggestion System
- **Input:** Age, Weight
- **Logic:** Checks if weight is within an ideal range for the age group and gives suggestions.
- **Example Output:**  
  `You are underweight for your age. Consider a healthy diet.`

---

### 2. 💸 Monthly Budget Planner
- **Input:** Monthly income
- **Logic:**  
  - `< ₹10,000` → Spend cautiously and save more.  
  - `₹10,000 – ₹30,000` → Balanced budget.  
  - `> ₹30,000` → Consider investing.
- **Example Output:**  
  `Your income is great! Consider investing in SIPs.`

---

### 3. 📱 Mobile Data Usage Alert System
- **Input:** Data usage in GB
- **Logic:**  
  - `< 5GB` → Low usage  
  - `5–15GB` → Normal usage  
  - `> 15GB` → Heavy usage
- **Example Output:**  
  `You are a heavy data user. Upgrade your plan.`

---

### 4. 🔐 Change Password Logic
- **Input:** Old password, New password, Confirm password
- **Logic:** Checks if old password is correct, verifies new password matches confirmation.
- **Example Output:**  
  `Password changed successfully.` or `Passwords do not match.`

---

## 📸 Output Screenshots
Screenshots for each task are saved in the `screenshots/` folder.

---

## 🚀 How to Run
1. Open `index.html` in a browser.
2. Follow the prompt instructions for each task.
3. View alerts for results.

---

## 🛠 Technologies Used
- HTML
- JavaScript
- prompt() & alert() for user interaction

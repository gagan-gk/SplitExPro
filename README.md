# SplitExPro
# 💸 Expense Splitter (Single-File Web App)

A **Splitwise-like expense splitter** built as a **single self-contained `index.html` file**.

No backend.  
No database.  
No build tools.  
No installation.

Just open the file in a browser and start using it.

---

## ✨ What Makes This Special

- ✅ **Only one file** (`index.html`)
- ✅ Works fully **offline**
- ✅ Data stored **locally in browser**
- ✅ Mobile-friendly UI
- ✅ Dark / Light mode with proper color inversion
- ✅ Smart settlement logic
- ✅ Excel export with full details

Perfect for quick use, sharing, or GitHub Pages hosting.

---

## 🚀 Features

### 👥 Members
- Add unlimited members
- Delete members anytime
- Removing a member automatically updates expenses & settlements

---

### 🧾 Expenses
- Add expenses with:
  - Amount
  - Paid by
  - Expense type
- Edit existing expenses
- Delete expenses
- Cancel edit safely (no accidental overwrite)

--- 

### 📂 Expense Types (Dynamic Forms)

#### 🚕 Travel
- Mode of transport (Bus / Train / Flight / Car / Other)
- From → To
- Date

#### 🍔 Food
- Place
- Food type (Breakfast / Lunch / Dinner / Snacks / Other)
- Date

#### 🛒 Other
- Expense category
- Place
- Date

> Fields appear **only when relevant** — clean & clutter-free UI.

---

### ⚖️ Split Options

#### 🔹 Split Equally
- Automatically divides the expense among all members

#### 🔹 Split Selected Members (Custom)
- Choose specific members
- Enter **custom amount per member**
- Non-selected members are excluded

✔ Clicking on text selects checkbox/radio  
✔ Entire card is clickable  
✔ Smooth toggle animation

---

### 🔄 Final Settlement (Smart Logic)

- Calculates **who should pay whom**
- Automatically cancels opposite dues  
  (A → B and B → A are adjusted)
- Grouped clearly per member
- Easy to understand, human-readable output

---

### 📊 Spending Analysis
- Individual total spending table
- Minimal **doughnut chart**
- Chart adapts automatically to Dark / Light mode
- Clean, non-distracting visualization

---

### 📤 Excel Export
Exports **everything** into a single Excel file:

**Sheets included:**
1. Expenses (full details)
2. Expense splits (member-wise)
3. Individual spending summary
4. Final settlement

Useful for records, sharing, or backup.

---

### 🌗 Dark / Light Mode
- One-click toggle
- Theme preference saved automatically
- All text, tables, and charts invert correctly
- No contrast or readability issues

---

### 💾 Data Storage
- Uses browser **localStorage**
- Data persists after refresh & reopen
- No server, no cloud, no login

Your data stays **only on your device**.

---

## 🛠️ Tech Used (All via CDN)

- HTML5
- CSS3
- JavaScript (Vanilla)
- Bootstrap 5
- Chart.js
- SheetJS (xlsx)

All included directly inside **one HTML file**.

---

## 📁 Project Structure

SplitExPro/index.html


That’s it.  
No other files required.

---

## 🌐 How to Use

### Option 1: Local
1. Download `index.html`
2. Double-click to open in browser
3. Start using

### Option 2: GitHub Pages
1. Create a GitHub repo
2. Upload `index.html`
3. Enable **GitHub Pages**
4. Open the generated link

---

## 🔐 Privacy
- No tracking
- No cookies
- No analytics
- No external storage

100% private.

---

## 🎯 Best For
- Friends trips
- Roommates
- Group outings
- Small events
- Personal expense tracking

---

## 📌 Possible Future Enhancements
- Excel import
- Monthly grouping
- PWA (installable app)
- Multi-currency support

---

## 📜 License
Free to use, modify, and share.

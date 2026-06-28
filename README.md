# 💼 Employee Salary & Payroll Management System

An Excel-based payroll management project built for **MS Transport**, covering **10 employees** for **September 2026**. The workbook automates salary calculation, deductions, advance salary handling, and payment tracking — delivering a structured payroll system with a Key Metrics summary sheet.

---

## 🔍 Problem Statement

Small and mid-sized organizations often manage payroll manually using scattered records, leading to errors in deductions, advance recovery, and payment tracking. This project simulates a real-world payroll task: structure employee salary data, automate calculations, track payment status per employee, and surface critical pending cases for management review.

---

## ⚙️ Process & Methodology

**1. Raw Data Setup**
- Recorded 10 employee entries with designation, bank account, basic salary, advance salary, extra period pay, days worked, and payment date.

**2. Salary Calculation Logic**
- Computed **One Day Salary** from basic salary ÷ 30 days.
- Applied **pro-rated deductions** based on days worked (absent days × one day salary).
- Calculated **Current Salary** after deductions.
- Added **Previous Salary** balance and **Extra Period** pay to derive **Payable Salary**.

**3. Payment Status Tracking**
- Recorded actual **Paid Salary** and derived **Pending Salary** per employee.
- Classified each employee as **Fully Paid**, **Partially Paid**, or **Unpaid**.

**4. Key Metrics Dashboard**
- Summarized total Payable, Paid, and Pending salary figures.
- Calculated paid vs unpaid percentage across the payroll.
- Identified **Critical Cases** (100% unpaid employees) for immediate attention.

---

## 📸 Screenshots

### Detail Sheet
![Detail Sheet](Project%20Screenshots/Detail%20Sheet.png)

### Cleaned Data
![Cleaned Data](Project%20Screenshots/Cleaned%20Data.png)

### Key Matrices
![Key Matrices](Project%20Screenshots/Key%20Matrices.png)

### Paid vs Unpaid
![Paid vs Unpaid](Project%20Screenshots/Paid%20vs%20Unpaid.png)

---

## 📈 Key Findings

| Metric | Value |
|---|---|
| Total Employees | 10 |
| Total Payable Salary | PKR 112,508 |
| Total Paid Salary | PKR 70,078 |
| Total Pending Salary | PKR 42,430 |
| Payment Completion Rate | 62.3% |
| Pending Rate | 37.7% |

**Payment Status Breakdown:**
- ✅ Fully Paid — 3 employees (30%)
- 🔶 Partially Paid — 5 employees (50%)
- ❌ Unpaid — 2 employees (20%)

**Critical Cases:**
- **Rida** — PKR 19,100 fully pending (100% unpaid)
- **Somira** — PKR 6,536 fully pending (100% unpaid)

---

## 🗂️ Workbook Structure

| Sheet | Description |
|---|---|
| Raw Data | 10 employee records with full salary breakdown, deductions, and payment tracking |
| Company Sheet | Formatted payroll register for MS Transport — September 2026 |
| Key Metrics | Summary dashboard with payment status breakdown, pending cases, and critical flags |

---

## 🛠️ Excel Features Used

| Feature | Purpose |
|---|---|
| Arithmetic Formulas | One day salary, deductions, current salary, pending salary |
| Conditional Logic | Payment status classification (Fully Paid / Partially Paid / Unpaid) |
| Percentage Calculations | Paid % and unpaid % per employee and overall |
| Structured Tables | Organized payroll register with clear sections |
| Summary Aggregations | SUM-based totals for payable, paid, and pending columns |

---

## 📁 Repository Structure

```
Employee-Salary-Payroll-Management/
│
├── Project Screenshots/
│   ├── Detail Sheet.png        # Formatted payroll register
│   ├── Cleaned Data.png        # Cleaned employee salary data
│   ├── Key Matrices.png        # Summary dashboard
│   └── Paid vs Unpaid.png      # Payment status chart
│
├── SALARY SHEET EXCEL FILE.xlsx  # Main workbook
├── SALARY SHEET CSV FILE.csv     # Raw dataset for use in other tools
└── README.md
```

---

## 💡 Business Insights

1. **Over a third of payroll is still pending** — 37.7% unpaid rate signals a cash flow or disbursement process issue worth addressing.
2. **Two employees are completely unpaid** — Rida and Somira together account for PKR 25,636 in critical pending salary requiring immediate action.
3. **Advance salary recovery adds complexity** — Tracking advance deductions alongside pro-rated absent day deductions demonstrates multi-variable payroll logic.

---

## 👤 Author

**Abdullah Dawar**
Aspiring Data Analyst | Excel • SQL • Power BI
[GitHub Profile](https://github.com/AbdullahDawar77)

---

*This project is part of a data analytics portfolio developed to demonstrate real-world data analysis skills for analyst roles.*

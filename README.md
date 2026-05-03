# Qa-Project-5-Mobile-Testing-Urban-Lunch

<div align="center">
  <video src="https://github.com/user-attachments/assets/61b46f4a-de93-48b2-b1ba-df12cb735bea" width="90%"></video>
  <p><b><i>🎥 Proper functioning of the Urban Lunch Application.</i></b></p>
</div>

## 📋 Project Description

This project involves quality assurance (QA) for Urban Lunch, a mobile application designed for managing and collecting food orders. The main focus is to validate the entire user flow, from selecting the pickup location to confirming the delivery.

---

### 📂 Project Resources
* **📋 Requirements:** [View Functional Requirements (PDF)](https://practicum-content.s3.us-west-1.amazonaws.com/new-markets/qa-sprint-5/ESP/2025/Requisitos_Urban.Lunch.pdf)

---

## ✅ Activities Performed

🔍 **Requirement Analysis:** Detailed examination of application specifications to ensure functionality meets design expectations.

📝 **Test Design:** Creation of strategic checklists to cover critical interface flows and business logic.

📑 **Test Execution:** Functional testing performed on both emulators (configured via Android Studio) and real devices.

🐛 **Defect Management:** Identification, documentation, and reporting of bugs using Jira for professional tracking of each finding's lifecycle.

## 📑 Test Planning & Strategy

<table width="100%">
<tr>
<td width="30%"><b>🎯 Scope</b></td>
<td>Manual functional and UI validation on <b>Urban Lunch</b>, ordering flows, including pickup point selection, cart management, order confirmation, order tracking, error handling, and user notifications.</td>
</tr>

<tr>
<td><b>🚫 Out of Scope</b></td>
<td>Backend database validation, API testing and test automation.</td>
</tr>

<tr>
<td><b>✅ Entry Criteria</b></td>
<td>Stable APK build available, test devices configured in Android Studio, requirements and user flows documented, and test management tools accessible.</td>
</tr>

<tr>
<td><b>🏁 Exit Criteria</b></td>
<td>All critical and high-priority test cases executed, all identified bugs reported in <b>Jira</b> and final status report completed.</td>
</tr>
</table>

## 📊 User Flow Coverage Report

| Feature | Status | Key Verifications |
|---------|--------|------------------|
| 📍 Pickup Point | ✅ Covered | Interactive map, restaurant updates, permissions |
| 🛒 Cart Management | ✅ Covered | Counters (+/-), cart persistence, button states |
| 🏁 Confirmation | ✅ Covered | Price calculation, delivery ETA, route map |
| 🚚 Order Tracking | ✅ Covered | Status transitions, notifications |
| 📦 Order Delivered | ✅ Covered | Feedback, Notifications, Page Update |
| ⚠️ Error Handling | ✅ Covered | Geolocation alerts, empty cart prevention |


<details>
<summary><b>🔍 Detailed Validation Coverage</b></summary>

### 📍 Pickup Point Selection
- Verified interactive map behavior.
- Validated restaurant selection updates footer.
- Confirmed location permission handling.

### 🛒 Item Selection & Cart Management
- Tested product listing display and navigation.
- Validated increment/decrement counters `+/-`.
- Verified cart state persistence.
- Checked `Next` button enabled/disabled logic.

### 🏁 Order Confirmation
- Verified total price calculation.
- Validated estimated delivery times.
- Confirmed route visualization.

### 🚚 Order Tracking
- Tested automatic status transitions.
- Verified order notifications.

### ⚠️ Error Handling
- Validated missing geolocation alerts.
- Tested empty cart order prevention.

</details>

---

## 📊 Test Execution Metrics

<details>
  <summary><b><i>Click here to view Pickup Point Selection details</i></b></summary>

#### 📝 Design Checklist

 | Category | Results |
  | :--- | :---: |
  | 🚀 **Total Tests Executed** | `25` |
  | ✅ Passed Cases | `25` |
  | 🐞 Failed Cases (Bugs Found) | `0` |
  | 🚨 Critical/High Severity Defects| `0` |

## 📂 Project Documentation
[Pickup Point Selection-Checklist](https://docs.google.com/spreadsheets/d/1YnWkKYql9U87yVCmZMRTsavQFeKwf_M_UKA6BB_blK0/edit?usp=sharing)

<p align="left">
  <img src="assets/images/Pickup Selection.png" alt="Pickup Selection" width="250">
  <p><b><i>Pickup Point Selection</i></b></p>
</p>

</details>


<details>
  <summary><b><i>Click here to view Cart Management details</i></b></summary>

#### 📝 Design Checklist

 | Category | Results |
  | :--- | :---: |
  | 🚀 **Total Tests Executed** | `51` |
  | ✅ Passed Cases | `50` |
  | 🐞 Failed Cases (Bugs Found) | `1` |
  | 🚨 Critical/High Severity Defects| `1` |

## 📂 Project Documentation
[Cart Management-Checklist](https://docs.google.com/spreadsheets/d/1z7sV3o_vwgm2JI-ackaNUQmYjuwB3v7KMIgQuaqV4zw/edit?usp=sharing)

</details>

<details>
  <summary><b><i>Click here to view Order Confirmation details</i></b></summary>

#### 📝 Design Checklist

 | Category | Results |
  | :--- | :---: |
  | 🚀 **Total Tests Executed** | `32` |
  | ✅ Passed Cases | `27` |
  | 🐞 Failed Cases (Bugs Found) | `5` |
  | 🚨 Critical/High Severity Defects| `2` |

## 📂 Project Documentation
[Order Confirmation-Checklist](https://docs.google.com/spreadsheets/d/13WMYoq_ECIT8L5oDD-S0yA41PdzGWXbwni0yAwbA9Ds/edit?usp=sharing)

</details>

<details>
  <summary><b><i>Click here to view Order Tracking details</i></b></summary>

#### 📝 Design Checklist

 | Category | Results |
  | :--- | :---: |
  | 🚀 **Total Tests Executed** | `36` |
  | ✅ Passed Cases | `26` |
  | 🐞 Failed Cases (Bugs Found) | `10` |
  | 🚨 Critical/High Severity Defects| `7` |

## 📂 Project Documentation
[Order Tracking-Checklist](https://docs.google.com/spreadsheets/d/13chGF6Mdgt8XWk215dCtcrbYhlYWqhxpYnTU6uV3mkI/edit?usp=sharing)

</details>


<details>
  <summary><b><i>Click here to view Order Delivered details</i></b></summary>

#### 📝 Design Checklist

 | Category | Results |
  | :--- | :---: |
  | 🚀 **Total Tests Executed** | `38` |
  | ✅ Passed Cases | `29` |
  | 🐞 Failed Cases (Bugs Found) | `9` |
  | 🚨 Critical/High Severity Defects| `4` |

## 📂 Project Documentation
[Order Delivered-Checklist](https://docs.google.com/spreadsheets/d/1rKohKycEtUbjq1blHGRyFyDMU3OK8csjkcvgoHD7O2E/edit?usp=sharing)

</details>




<details>
  <summary><b><i> 🛑 Click here to view Bug Report: Adding dish to the order list details</i></b></summary>

  ## 🐛 [ID:P5-2] – Critical Bug (Blocker) Adding dish to the order list, In Saucer details screen (Cart Management)

* **Severity:** 🛑 **Critical** (Breaks the core conversion flow).
* **Priority:** **High** ⬆️

### 📝 Description
"Next" button remains disabled after adding at least one item to the order list.

### 🎬 Evidence & Technical Analysis
This recording shows a blocker issue where users can add items successfully, but the "Next" button remains disabled.

<div align="center">
  <video src="https://github.com/user-attachments/assets/823d642b-a109-4204-b632-df7e7a436135" width="75%"></video>
</div>

---

### 🛠️ Bug Details (Expected vs. Actual)

**Expected Result:**
After adding at least one item, the **"Next"** button becomes enabled/active, allowing the user to continue to the order confirmation flow.

**Actual Result:**
The **"Next"** button remains disabled even after adding one or more items to the order list, preventing progression to the next screen.

---

**Steps to Reproduce:**

1. Open the application.
2. Navigate to the food/item selection screen.
3. Go to Saucer details screen.
4. Select any available product.
5. Tap the **"+"** button to add at least one item to the cart/order list.
6. Observe the **"Next"** button status.

**Defect Impact:**
Users are blocked from continuing the purchase flow after selecting items. This prevents order completion, directly affecting revenue generation and rendering the primary ordering flow unusable.


### 💻 Testing Environment.
* **Tools:** Android Studio.
* **Device:** Android Emulator
* **Build:** APK Test Build
* **OS:** Linux Mint.

 
</div>
</details>













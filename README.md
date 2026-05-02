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







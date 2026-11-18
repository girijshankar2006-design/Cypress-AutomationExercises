# Cypress E2E Automation — AutomationExercise

## Project Description
This repository contains an automated End-to-End (E2E) web testing suite built using **Cypress** (JavaScript) and **Mochawesome HTML Reporter**. The suite automates 10 core user journeys—including product catalog navigation, search validation, boundary edge cases, negative authentication checks, shopping cart operations, and newsletter subscription—on [AutomationExercise.com](https://automationexercise.com/).

## Test Coverage (10 Automated Cases)
- **TC-01:** Verify home page load and featured product visibility
- **TC-02:** Navigate to the All Products catalog page
- **TC-03:** Search for a valid product (`"Tshirt"`)
- **TC-04:** Boundary test for non-existent product search (`0` results)
- **TC-05:** Inspect single product details and pricing
- **TC-06:** Negative test for invalid login credentials
- **TC-07:** Negative test for duplicate email registration
- **TC-08:** Add product to shopping cart and verify cart table row
- **TC-09:** Remove product from shopping cart and verify empty state
- **TC-10:** Verify footer newsletter subscription alert

## Tech Stack
- **Framework:** Cypress (E2E Testing)
- **Language:** JavaScript (ES6)
- **Reporting:** Mochawesome HTML Reporter
- **Target Application:** `https://automationexercise.com/`

## Setup & Execution
1. Clone the repository and install dependencies:
   ```bash
   npm install

# Test Plan – Sauce Demo

## 1. Introduction
The main goal of the testing activities is to provide stakeholders with information regarding the quality of the delivered product. The purpose of this test plan is to ensure the quality and correct functionality of the website. The tests aim to verify the functionality, performance, and usability of the product search, account creation, and order processing to ensure a seamless user experience. This document gathers key information about testing activities, detailing all software components subject to verification and the types of tests to be conducted.

---

## 2. Scope of Testing

| Category | Test Type | Status | Description / Target Area |
| :--- | :--- | :---: | :--- |
| **Functional** | Unit Testing | In-Scope | Verifies individual component logic. |
| **Functional** | Integration Testing | In-Scope | Verifies data flow between cart and backend service. |
| **Functional** | End-to-End (E2E) | In-Scope | Validates complete user path (Search → Cart → Checkout). |
| **Non-Functional** | Performance | In-Scope | Checks page load times and response latency. |
| **Non-Functional** | Compatibility | In-Scope | Verifies layout and behavior across browsers/devices. |
| **Execution Method**| Test Automation | **Out-of-Scope** | Excluded due to budget constraints. |
| **Non-Functional** | Security Testing | **Out-of-Scope** | Excluded from the current testing sprint. | 

---

## 3. Test Item
The component subject to testing is the [Sauce Demo Shopify Store](https://sauce-demo.myshopify.com/) website.

---

## 4. Pass / Fail Criteria
- **Pass:** All test cases completed successfully; no critical bugs found.
- **Fail:** Detection of critical bugs (e.g., inability to search, incorrect results, non-functioning filters) or occurrence of more than 5 high-priority bugs.

---

## 5. Entry and Exit Criteria

### 5.1. Entry Criteria
- Defined business and technical requirements (documentation).
- Ready website open in the test environment.
- Prepared test cases.

### 5.2. Exit Criteria
- Execution of all planned tests.
- Resolution of all critical and high-priority bugs.
- All components meet the specified assumptions in accordance with the documentation.
- Generation of the final test execution report.

---

## 6. List of Functional Requirements to be Tested
- Searching and adding products to the cart.
- Displaying results according to expected criteria.
- Operation of filters (price, star rating, property type).
- Operation of sorting (by rating, distance, reviews).
- Displaying detailed product information (photos, description, ratings, availability).
- Handling errors or incomplete input data.
- Compatibility with different browsers and mobile devices.
- Search engine speed and result loading performance.

---

## 7. Test Environment
- **Operating Systems:** Windows
- **Browsers:** Edge
- **Devices:** laptop
- **Test Database:** Test environment with a prepared database simulating real-world operating conditions.

---

## 8. Test Schedule
- **Stage 0:** Verification of functionality based on User Stories (documentation)
- **Stage 1:** Preparation of test cases and test environment
- **Stage 2:** Functional testing
- **Stage 3:** Performance and usability testing
- **Stage 4:** Bug reporting and verification
- **Stage 5:** Regression testing

---

## 9. Test Report
The final report will include:
- Test plan summary
- List of test cases and their results (pass / fail)
- List of identified bugs along with their priorities
- Conclusions and recommendations

---

## 10. List of Tools
- **Test Management:** Jira, TestLink
- **Performance Testing:** Postman
- **Defect Tracking:** Jira, TestLink

---

## 11. Incident / Bug Management
All detected bugs will be reported and tracked in **JIRA**.

### Bug management process:
1. **Bug Reporting** – detailed description and attachments (screenshots, logs, video).
2. **Priority Assignment** – Critical, High, Medium, Low.
3. **Bug Fixing** – carried out by the development team.
4. **Verification** – re-test of the fixed bug conducted by the testing team.

---

## 12. Roles and Responsibilities
- **Test Manager:** Planning and supervising the testing process.
- **Testers:** Preparing test cases, executing tests, reporting bugs.
- **Developers:** Fixing reported bugs.
- **Business Analyst:** Verifying compliance of results with business requirements.

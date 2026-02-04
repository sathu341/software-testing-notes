# Introduction to Software Testing & Principles of Testing

## 1. Introduction to Software Testing

### What is Software Testing?
**Software Testing** is the process of evaluating a software application to identify defects (bugs) and ensure that the software works according to the specified requirements.

> **Simple Definition:**  
Software Testing verifies and validates that a software product is free from defects, meets user requirements, and delivers quality.

---

### Why Software Testing is Important
- To identify bugs before release
- To improve software quality
- To ensure correct functionality
- To reduce development and maintenance cost
- To increase customer satisfaction
- To prevent business loss

**Real-Life Example:**  
In an online banking application, if money is debited but not credited to the receiver, it can cause serious financial loss. Testing helps prevent such issues.

---

### What Happens Without Testing?

| Without Testing | With Testing |
|---------------|--------------|
| More defects | Fewer defects |
| Poor user experience | Better user experience |
| Customer complaints | Customer trust |
| Financial loss | Business growth |

---

### Error, Defect, Bug & Failure

| Term | Meaning | Example |
|----|--------|--------|
| Error | Mistake made by developer | Wrong calculation logic |
| Defect / Bug | Error in the software | Incorrect interest calculation |
| Failure | Software does not work | Application crashes |

---

### Verification & Validation

#### Verification
> **Are we building the product correctly?**

- Static process
- No code execution
- Reviews, inspections, walkthroughs

**Example:**  
Checking requirement and design documents.

---

#### Validation
> **Are we building the correct product?**

- Dynamic process
- Code execution required
- Actual testing of software

**Example:**  
Running the login functionality of an application.

---

### Types of Software Testing

#### Manual Testing
- Done manually by testers
- No automation tools used

**Example:**  
Tester manually checks login using valid and invalid inputs.

---

#### Automation Testing
- Performed using tools like Selenium, Cypress
- Saves time and effort

**Example:**  
Automated script tests login functionality 100 times.

---

### When is Testing Performed?
Testing is performed **throughout the Software Development Life Cycle (SDLC)**.

---

## 2. Principles of Software Testing

There are **7 fundamental principles of software testing**.

---

### Principle 1: Testing Shows Presence of Defects
Testing can find defects but cannot prove that software is completely defect-free.

**Example:**  
Even after testing a calculator app, some hidden bugs may still exist.

---

### Principle 2: Exhaustive Testing is Impossible
It is impossible to test all possible input combinations.

**Example:**  
Login page with 100 usernames and 100 passwords results in 10,000 combinations.

---

### Principle 3: Early Testing Saves Time and Money
Testing should start as early as possible in the SDLC.

**Example:**  
Fixing a bug in the design phase is cheaper than fixing it after deployment.

---

### Principle 4: Defect Clustering
Most defects are found in a small number of modules.

**Example:**  
Payment module may contain 70% of total bugs.

---

### Principle 5: Pesticide Paradox
Running the same tests repeatedly will not find new defects.

**Example:**  
Repeated login tests may not detect bugs in password reset.

**Solution:**  
Regularly update and improve test cases.

---

### Principle 6: Testing is Context Dependent
Testing approach depends on the type of application.

| Application | Testing Focus |
|------------|---------------|
| Banking App | Security, accuracy |
| Game App | Performance, usability |
| Hospital App | Data correctness |

---

### Principle 7: Absence of Errors Fallacy
A bug-free system is useless if it does not meet user requirements.

**Example:**  
An application works perfectly but is difficult to use.

---

## Real-Time Example: Online Shopping Application

| Feature | Test Scenarios |
|------|---------------|
| Login | Valid and invalid credentials |
| Cart | Add / remove items |
| Payment | Card, UPI, failure cases |
| Performance | Page load time |
| Security | SQL injection, authentication |

---

## Summary
- Software testing ensures quality and reliability
- Testing must start early
- All defects cannot be found
- Focus on critical and high-risk modules
- Principles guide effective testing

---

**Author:** Sathish Chandran  
**Purpose:** Academic & Interview Preparation

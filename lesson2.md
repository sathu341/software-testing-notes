# Verification and Validation  
## Static Testing & Dynamic Testing

---

## 1. Verification

### What is Verification?
**Verification** is the process of checking whether the software is being built **correctly according to specifications and design**.

> **Key Question:**  
**Are we building the product correctly?**

Verification focuses on **documents and plans**, not on executing the code.

---

### Characteristics of Verification
- Static process
- No code execution
- Done in early stages of SDLC
- Prevents defects
- Focuses on correctness of design and requirements

---

### Verification Activities
- Requirement analysis review
- Design review
- Code review
- Walkthroughs
- Inspections

---

### Example of Verification
**Online Shopping App**
- Check requirement document:  
  "User must receive order confirmation email"
- Review design diagram to ensure email service is included

📌 No software is executed here.

---

## 2. Validation

### What is Validation?
**Validation** is the process of checking whether the **actual software product meets the user’s needs and expectations**.

> **Key Question:**  
**Are we building the correct product?**

Validation involves **executing the software**.

---

### Characteristics of Validation
- Dynamic process
- Code execution required
- Performed after development
- Finds defects
- Focuses on user requirements

---

### Validation Activities
- Unit testing
- Integration testing
- System testing
- User Acceptance Testing (UAT)

---

### Example of Validation
**Online Shopping App**
- Place an order
- Check if confirmation email is actually received

📌 Software is executed to confirm behavior.

---

## 3. Static Testing

### What is Static Testing?
**Static Testing** is a testing technique where the software is **not executed**.  
It is used to find defects in **documents, design, and code**.

---

### Static Testing Includes
- Requirement reviews
- Design reviews
- Code inspections
- Walkthroughs

---

### Advantages of Static Testing
- Finds defects early
- Reduces cost
- Improves quality
- Saves time

---

### Example of Static Testing
**Login Module**
- Review code and identify missing password validation
- Review requirement document for unclear statements

---

## 4. Dynamic Testing

### What is Dynamic Testing?
**Dynamic Testing** is a testing technique where the software **is executed** to find defects.

---

### Dynamic Testing Includes
- Functional testing
- Non-functional testing
- Manual testing
- Automation testing

---

### Types of Dynamic Testing
- Unit Testing
- Integration Testing
- System Testing
- Acceptance Testing

---

### Example of Dynamic Testing
**Login Page**
- Enter valid username and password → login successful
- Enter invalid password → error message displayed

---

## 5. Static Testing vs Dynamic Testing

| Feature | Static Testing | Dynamic Testing |
|------|---------------|----------------|
| Code execution | ❌ No | ✅ Yes |
| Performed on | Documents, code | Running application |
| Type | Preventive | Detective |
| Defects found | Early-stage defects | Runtime defects |
| Cost | Low | High |
| Examples | Reviews, inspections | Unit, system testing |

---

## 6. Verification vs Validation

| Feature | Verification | Validation |
|------|-------------|------------|
| Question | Are we building it right? | Are we building the right product? |
| Process type | Static | Dynamic |
| Execution | No | Yes |
| Focus | Specification & design | User requirements |
| Performed by | Developers / QA | Testers / Users |

---

## 7. Real-Time Example (Complete Flow)

### Hospital Management System

#### Verification
- Review requirement: "Doctor can view patient history"
- Review database design for patient records

#### Validation
- Login as doctor
- Open patient profile
- Verify patient history is displayed correctly

---

## 8. Exam-Oriented Key Points
- Verification = Static testing
- Validation = Dynamic testing
- Verification prevents defects
- Validation detects defects
- Both are essential for quality software

---

## Summary
- Verification ensures correctness of development process
- Validation ensures correctness of final product
- Static testing finds defects early
- Dynamic testing confirms software behavior
- Both improve software quality

---

**Author:** Sathish Chandran  
**Use Case:** MCA / IGNOU / BCA / Software Testing Interviews

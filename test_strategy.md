# Test Strategy Document

## Application

Construction Payroll HRMS

## Objective

The primary goal is to ensure that workers receive accurate salaries, payslips, and attendance records. Any failure in payroll can directly impact employees' income and company trust.

## Top 5 Critical Flows (Ranked by Business Impact)

### 1. Payroll Calculation

**Who gets hurt:** Employees and Payroll Manager

**Worst consequence:** Incorrect salary calculation can result in underpayment or overpayment, causing financial loss, employee dissatisfaction, and payroll disputes.

### 2. Attendance & Overtime Processing

**Who gets hurt:** Employees

**Worst consequence:** Missing attendance or overtime records can lead to salary errors and loss of employee trust.

### 3. Payslip Generation

**Who gets hurt:** Employees and HR Team

**Worst consequence:** Employees receive incorrect or incomplete payslips, making payroll verification difficult.

### 4. Employee Onboarding

**Who gets hurt:** HR Team and New Employees

**Worst consequence:** Employee records are incomplete or incorrect, affecting attendance tracking and payroll processing.

### 5. Employee Exit / Payroll Stop

**Who gets hurt:** Company Finance Team

**Worst consequence:** Ex-employees continue receiving salary or remain active in the system, causing financial loss.

## Automation vs Manual Testing

### Automate

* Payroll calculation validation
* Employee create/update/delete flows
* Payslip generation verification
* API validation and business rule checks

### Manual Testing

* Exploratory testing
* UI usability checks
* Edge-case investigations
* New feature validation

### Keeping CI Fast

* Run critical smoke tests on every commit.
* Execute full regression suite nightly.
* Prioritize high-risk business flows.
* Avoid long-running UI tests unless necessary.

## What I Will Not Test

* Cosmetic UI differences that do not affect business functionality.
* Browser combinations with negligible user usage.
* Low-risk visual styling changes.

Reason: Testing effort should focus on payroll accuracy, employee data integrity, and critical business workflows.


# End-to-End Test Suite

## Test Case 1: Employee Onboarding

### Steps

1. Login as HR Admin.
2. Navigate to Employee Management.
3. Add a new employee with valid details.
4. Save the employee record.

### Expected Result

The employee is successfully created and appears in the employee list.

---

## Test Case 2: Attendance to Payroll Flow

### Steps

1. Login as HR Admin.
2. Create a new employee.
3. Mark attendance for 5 working days.
4. Add overtime hours.
5. Run payroll generation.

### Expected Result

Attendance and overtime data are correctly reflected in the payroll calculation.

---

## Test Case 3: Leave Approval Flow

### Steps

1. Employee submits a leave request.
2. Manager approves the request.
3. Generate payroll.

### Expected Result

Approved leave is correctly considered during payroll processing.

---

## Test Case 4: Payslip Generation

### Steps

1. Complete payroll processing.
2. Generate payslip for the employee.

### Expected Result

Payslip displays correct salary, overtime, deductions, and employee information.

---

## Test Case 5: Employee Exit Flow

### Steps

1. Mark employee as inactive or exited.
2. Generate payroll for the next cycle.

### Expected Result

Inactive employees should not receive salary payments.


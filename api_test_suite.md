# API Test Suite

## Employee Creation API

### Positive Test

Create employee with valid details.

Expected Result:
Employee created successfully.

### Negative Test

Create employee without mandatory fields.

Expected Result:
Validation error returned.

---

## Attendance API

### Positive Test

Submit valid attendance record.

Expected Result:
Attendance saved successfully.

### Negative Test

Submit attendance with invalid employee ID.

Expected Result:
Error message returned.

---

## Overtime API

### Positive Test

Submit valid overtime hours.

Expected Result:
Overtime recorded successfully.

### Negative Test

Submit negative overtime hours.

Expected Result:
Validation error displayed.

---

## Payroll API

### Positive Test

Generate payroll for valid employee.

Expected Result:
Payroll generated successfully.

### Negative Test

Generate payroll for inactive employee.

Expected Result:
System prevents payroll generation.


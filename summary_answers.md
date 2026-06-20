
# Summary Sheet

## 1. What does this HRMS exist to deliver, and to whom?

This HRMS exists to deliver accurate payroll to workers. Every feature, including attendance, overtime, leave, and employee management, ultimately supports correct salary payments to the people who depend on them for their livelihood.

## 2. What is the single most dangerous bug pattern you found across your testing?

The most dangerous bug pattern is incorrect data flowing through multiple modules without validation. For example, wrong attendance or overtime data can silently affect payroll calculations and result in incorrect payments.

## 3. Which test in your suite are you most proud of, and why?

I am most proud of the attendance-to-payroll end-to-end test. It verifies that attendance and overtime data are correctly reflected in payroll calculations and helps prevent workers from being underpaid or overpaid.

## 4. What did you choose NOT to automate, and why was that the right call?

I chose not to automate exploratory and visual UI testing. These areas benefit more from human observation, while automation effort is better spent protecting critical payroll workflows.

## 5. What's one thing in your submission that you're not fully confident about, and why you included it anyway?

I am not fully confident about the API test coverage because I did not have access to a real production API specification. I included it because API validation is an important part of quality engineering and I wanted to demonstrate my testing approach.

## 6. What changed between your first approach and your final submission?

Initially, I focused on individual features. Later, I shifted my focus to business-critical workflows and risk-based testing because payroll accuracy is more important than testing isolated screens.

## 7. What do you not know about quality engineering or construction payroll that you would need to learn before doing this job?

I would need to learn:

1. Construction payroll regulations and compliance rules.
2. Real-world overtime and wage calculation policies.
3. Advanced automation and CI/CD practices used in production QA teams.

## 8. If you had one more day, what would you test that you didn't get to?

I would spend more time testing payroll edge cases involving overtime, leave adjustments, and employee status changes. These scenarios are important because they directly affect salary accuracy and employee trust.

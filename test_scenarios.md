# Test Scenarios

I tested the Home Credit LAP voice agent with different customer responses to check how it handles eligibility.

## 1. Customer Meets Basic Eligibility

**Input:** The customer has a residential property, joint ownership, original documents, requests ₹50 lakh, is salaried, receives salary in a bank account, estimates the property value at ₹1 crore, and prefers a 10-year tenure.

**Expected Result:** The agent should complete all seven checkpoints and explain that the customer meets the preliminary eligibility criteria.

**Status:** PASS

## 2. Agricultural Property

**Input:** The customer wants to use agricultural property for the loan.

**Expected Result:** The agent should explain that agricultural property does not meet the offer criteria and end the qualification process.

**Status:** PASS

## 3. Cash-Based Income

**Input:** The customer mainly receives income in cash rather than through a bank account.

**Expected Result:** The agent should explain the bank-income requirement and stop the qualification process.

**Status:** PASS

## 4. Original Property Documents Unavailable

**Input:** The customer does not have the original property documents.

**Expected Result:** The agent should explain that the original documents are required and end the qualification process.

**Status:** Tested — transcript verification pending

## 5. Existing Loan / Balance Transfer

**Input:** The customer already has a loan against the property and wants assistance with the existing loan.

**Expected Result:** The agent should stop the regular eligibility flow, refer the customer to a loan-transfer specialist, and end the call.

**Status:** PASS

## Conclusion

The tests cover successful preliminary eligibility, immediate disqualification cases, and existing loan transfer requests. The agent does not guarantee final loan approval, which remains subject to verification and the lender's decision.

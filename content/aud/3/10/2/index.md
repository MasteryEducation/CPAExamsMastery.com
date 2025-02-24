---
title: "Purchases, Expenditures, and Payroll Cycles"
description: "Master key auditing procedures to identify risks, perform tests of details, and apply analytical techniques for purchases, expenditures, and payroll cycles."
linkTitle: "10.2 Purchases, Expenditures, and Payroll Cycles"
date: 2025-02-07
type: docs
nav_weight: 1002
license: "© 2024 Tokenizer Inc. CC BY-NC-SA 4.0"
---

## 10.2 Purchases, Expenditures, and Payroll Cycles

In this section, we dive into the critical areas of purchases and payroll—the processes by which organizations acquire goods and services, pay compensation to their workforce, and record related financial transactions. Auditors must focus on the risks, internal controls, and testing strategies that ensure expenditures are valid, accurately recorded, and properly authorized. An understanding of the full cycle—from purchase requisitions to vendor payments and from timesheets to payment of employee wages—will equip you to detect misstatements, both accidental and fraudulent, that could materially impact the financial statements.

This discussion builds on the broader concepts of assessing risk and designing an effective audit plan, as introduced in Chapters 4 through 7. We will explore the typical documentation flow in a purchases-and-payroll environment, identify high-risk areas for misstatement, and describe various substantive procedures—both tests of details and analytical approaches—that auditors commonly employ.

--------------------------------------------------------------------------------

### 1. Overview of the Purchases and Expenditures Cycle
Purchases and expenditures typically include the following phases:
1. Purchase Requisition and Approval: Internal departments initiate purchase requests, which must be authorized by appropriate personnel.  
2. Purchase Order (PO) Creation: A formal PO is generated and sent to the vendor, detailing quantities, prices, and other relevant terms.  
3. Receipt of Goods or Services: The entity’s receiving department acknowledges the delivery and inspects it for quality and quantity control.  
4. Vendor Invoice Matching: A three-way match typically compares the purchase order, receiving report, and invoice details to confirm accuracy.  
5. Payment Processing: The accounts payable department approves and issues payment to the vendor within agreed-upon terms.

Below is a simplified diagram illustrating the typical flow of documents in a purchase-to-pay cycle:

```mermaid
flowchart LR
    A[Purchase Requisition] --> B[Purchase Order]
    B --> C[Receiving Report]
    C --> D[Vendor Invoice]
    D --> E[Accounts Payable Recording]
    E --> F[Payment Authorization]
    F --> G[Payment Issued to Vendor]
    G --> H[Accounting Records Updated]
```

#### Key Risks
• Completeness: If invoices or accrued expenses are not recorded, expenditures could be understated.  
• Accuracy: Risk arises when three-way matching (PO, receiving report, invoice) is bypassed or performed incorrectly, leading to over- or under-payment.  
• Cutoff: Costs might be recorded in the wrong period if goods received near year-end are not matched to the correct accounting period.  

--------------------------------------------------------------------------------

### 2. Overview of the Payroll Cycle
The payroll cycle involves activities such as hiring employees, capturing time and attendance data, authorizing payroll changes, calculating wages, and disbursing pay. An auditor typically focuses on ensuring that only bona fide employees are paid for hours actually worked or services rendered.

Below is a simplified process flow for the payroll cycle:

```mermaid
flowchart LR
    A[Employee Master File Setup] --> B[Timekeeping & Attendance]
    B --> C[Payroll Calculation]
    C --> D[Payroll Register]
    D --> E[Payment Documentation (Checks/Direct Deposits)]
    E --> F[Posting to GL & Payroll Expenses]
```

#### Key Risks
• Completeness and Accuracy: Unauthorized pay adjustments or incorrect payroll rates can lead to misstatements.  
• Fraud Risk: Ghost employees or manipulation of timesheets represent payroll-specific fraud scenarios.  
• Classification: Distinguishing between employee vs. contractor, wages vs. benefits, or capitalizable labor costs vs. operating expenses.

--------------------------------------------------------------------------------

### 3. Typical Risk Areas and Red Flags

#### 3.1 Expenditure-Related Risks

1. Understatement of Liabilities (Completeness)  
   • Failure to record goods received or invoices at period-end.  
   • High volume of manual accrual entries that could be susceptible to error or manipulation.  

2. Accuracy and Validity  
   • Inconsistent or inaccurate matching of invoices to receiving reports and purchase orders.  
   • Inappropriately authorized master vendor file changes that lead to incorrect or fraudulent payments.

3. Fraud Indicators  
   • Duplicate or fictitious invoices.  
   • Invoices for goods or services never received.  
   • Collusion between purchasing and receiving personnel to approve illegitimate transactions.

#### 3.2 Payroll-Related Risks

1. Payroll Fraud (Ghost Employees)  
   • Inadequate segregation of duties, allowing payroll personnel to add nonexistent employees.  
   • Unauthorized changes to wage rates or payment details.  

2. Inaccurate Wage Calculations  
   • Manual discrepancies in time-sheets or automated timekeeping system overrides.  
   • Tax withholdings and deductions miscalculated or improperly recorded.

3. Regulatory Compliance  
   • Errors in the accrual of vacation, overtime, or pension liabilities.  
   • Failure to adhere to labor regulations or controls over employee classification (exempt vs. non-exempt).

--------------------------------------------------------------------------------

### 4. Substantive Procedures for Purchases and Expenditures

#### 4.1 Tests of Details

• Tracing and Vouching  
  – Tracing: Moving from source documents (e.g., purchase orders, receiving slips) into the accounting records to check completeness.  
  – Vouching: Examining entries in the ledger and matching them back to original documents to verify existence and occurrence.

• Recalculation and Reperformance  
  – Auditors may recalculate invoice extensions (quantity × price), discounts, and taxes to ensure arithmetic accuracy.  
  – Reperform the three-way match process to confirm the recorded payable matches the PO, receiving report, and vendor invoice.

• Cutoff Testing  
  – Inspect transactions around period-end to ensure expenses and payables are recognized in the appropriate accounting period.

• Search for Unrecorded Liabilities  
  – Review disbursements made after period-end to identify unrecorded payables.  
  – Inquire about procedures for capturing vendor invoices that arrive after the statement date.

#### 4.2 Analytical Procedures
• Ratio Analysis: Compare current year’s cost of goods sold as a percentage of sales or to prior years’ data; large variances may indicate unrecorded or misstated purchases.  
• Trend Analysis: Look for unusual changes in average days payable outstanding or fluctuations in key supplier balances that are inconsistent with operational data.  

Below is a simple table example illustrating a year-over-year ratio comparison:

| Description                     | Year 1    | Year 2    | Year 3    |
|--------------------------------|-----------|-----------|-----------|
| Cost of Goods Sold (COGS)      | $1,500,000| $1,800,000| $2,150,000|
| Sales                           | $2,800,000| $3,000,000| $3,600,000|
| COGS as % of Sales             | 53.6%     | 60.0%     | 59.7%     |
| Observation                     | Normal    | Slightly ↑| Stable    |

Significant fluctuations in the COGS ratio beyond historical norms or industry averages may prompt additional investigation.

--------------------------------------------------------------------------------

### 5. Substantive Procedures for Payroll

#### 5.1 Tests of Details

• Employee Master File Testing  
  – Confirm authorized wage rates, job classifications, and active/inactive status from HR records.  
  – Sample employee profiles to verify existence, ensuring “ghost employees” do not exist.

• Payroll Recalculation  
  – Recalculate gross pay, tax withholdings, and deductions for a sample of employees based on timecards or electronic timekeeping files.  
  – Verify the pay rate against authorized HR documentation.  
  – Check the accuracy of withholdings (income tax, social security, etc.) and ensure timely remittance to taxing authorities.

• Authorization Controls  
  – Verify proper approvals for new hires, terminations, wage rate changes, and overtime authorizations.  
  – Check for management oversight (e.g., department head sign-off on time sheets).

#### 5.2 Analytical Procedures
• Payroll Ratio Trends  
  – Compare total payroll expenses to total revenues or total operating expenses over multiple periods. Sudden spikes or drops may signify errors or fraud.  
  – Evaluate average wage rate per employee classification over time.  

• Budget vs. Actual Comparison  
  – Identify significant variances in labor costs. Large unexplained variances may point to unauthorized bonus payouts, misclassifications, or inflated headcounts.

--------------------------------------------------------------------------------

### 6. Best Practices and Common Pitfalls

#### 6.1 Best Practices
• Maintain robust segregation of duties: Separate responsibilities for creating purchase orders, receiving goods, approving invoices, and issuing checks.  
• Implement a strict vendor approval process: Centralize the creation and management of a vendor master file to reduce the risk of fictitious vendors.  
• Automate time tracking: Reduce manual interventions and potential for error or manipulation in payroll by using electronic timekeeping systems.  
• Conduct periodic surprise audits: Perform unannounced visits to inventory warehouses or conduct spot checks on payroll data to increase the deterrent for fraud.

#### 6.2 Common Pitfalls
• Overlooking small or old outstanding payables: These can accumulate masking fraudulent or erroneous transactions.  
• Relying solely on system controls without periodic revalidation: Automated processes can fail or be overridden.  
• Insufficient scrutiny of changes to the vendor master file: Unauthorized vendors can lead to significant fraudulent payments.  
• Not reconciling gross payroll to payroll tax forms: This can reveal misstatements or compliance gaps with withholding taxes.

--------------------------------------------------------------------------------

### 7. Real-World Examples and Case Studies

• A manufacturing entity discovered it had been paying for non-existent office supplies for nearly two years. The perpetrator colluded with a vendor to issue phony invoices. The company had not enforced its three-way matching policy consistently, resulting in significant cash outflows for fictitious goods.  
• A retailer found dozens of ghost employees added to the payroll system by one HR staff member who had the sole authority to hire and set up new employees. When questioned about rising labor costs, store managers discovered employees in their departments that no one had ever met.

--------------------------------------------------------------------------------

### 8. Glossary of Key Terms

• **Tracing**: Starting with original source documentation (e.g., purchase orders, receiving reports) and following transactions forward into the general ledger to ensure completeness.  
• **Three-Way Match**: Matching purchase order, receiving report, and invoice amounts before recording the liability or processing payment.  
• **Ghost Employees**: Fraud scenario where nonexistent workers are set up in the payroll system, leading to fraudulent wage payments.  
• **Vendor Master File**: Centralized list of approved vendors containing critical details such as vendor name, address, and account info.

--------------------------------------------------------------------------------

### 9. References and Resources

#### 9.1 Official References
- AU-C Section 330, “Performing Audit Procedures in Response to Assessed Risks and Evaluating the Audit Evidence Obtained”  
- AU-C Section 500, “Audit Evidence”

#### 9.2 Additional Resources
- AICPA Audit Guide: Government Auditing Standards and Single Audits (for further guidance on payroll and compliance testing in governmental entities).  
- Articles on controlling the purchase-to-pay process in the CPA Journal (various authors and issues).

--------------------------------------------------------------------------------

## Quiz on Purchases, Expenditures, and Payroll Cycles

{{< quizdown >}}

### Which of the following best describes a significant risk when auditing the purchases cycle?

- [ ] Exceeding the budget in minor expense categories
- [x] Understating liabilities by not recording goods received or invoices
- [ ] Having too many purchase orders requested by different departments
- [ ] Recording all liabilities at year-end

> **Explanation:** Understatement of liabilities is a key risk because unrecorded invoices can potentially understate expenses and payables.  

### In a three-way matching procedure, which three documents are compared?

- [ ] Bank statement, purchase order, material requisition
- [x] Purchase order, receiving report, vendor invoice
- [ ] Receiving report, sales invoice, vendor invoice
- [ ] Sales order, sales invoice, remittance slip

> **Explanation:** Three-way matching requires reconciling the purchase order with the receiving report and vendor invoice to ensure accurate and authorized payments.  

### What is the primary objective of tracing in the context of expenditures?

- [x] To verify completeness by following source documents into the books
- [ ] To ensure validity of recorded expenses by starting in the general ledger
- [ ] To confirm expense cutoff for the correct periodic reporting
- [ ] To recalculate employee wage rates for accuracy

> **Explanation:** Tracing starts from original source documents and moves forward to posting in the general ledger, ensuring that all proper transactions have been recorded.  

### If an auditor suspects ghost employees in the payroll system, which procedure is most relevant?

- [ ] Inspecting vendor invoices associated with employee reimbursements
- [x] Verifying the existence and authorization of employees listed in the HR master file
- [ ] Performing physical inventory counts at year-end
- [ ] Comparing total payroll expense to cost of goods sold

> **Explanation:** Ghost employees involve fraudulent additions to the personnel directory. Checking the HR system for legitimate hires is the most effective procedure.  

### Which analytical procedure would best detect unusual spikes in payroll costs?

- [ ] Recalculation of the three-way match
- [x] Comparing payroll expense ratios to sales or prior periods
- [ ] Examining material invoices at year-end
- [ ] Preparing a bank reconciliation

> **Explanation:** Analytical procedures, such as trend analysis of total payroll expense ratios over time, help identify unusual variances.  

### In testing accounts payable, a search for unrecorded liabilities commonly involves:

- [x] Reviewing subsequent cash disbursements after period-end
- [ ] Reconciling the payroll register to the HR file
- [ ] Matching cash deposit slips to sales invoices
- [ ] Examining credit memos for returns

> **Explanation:** Reviewing disbursements made after period-end helps detect invoices or goods received that should have been accrued at year-end but were not.  

### Which procedure explicitly checks for arithmetic accuracy of invoice calculations?

- [x] Recalculation
- [ ] Confirmation
- [x] Reperformance
- [ ] Observation

> **Explanation:** Recalculation and reperformance are designed to verify the arithmetic accuracy of transactions (e.g., verifying price, discount, quantity).  

### A best practice to prevent unauthorized payments in the purchase cycle is:

- [x] Segregating duties between accounts payable, purchasing, and receiving
- [ ] Having the same individual approve invoices and sign checks
- [ ] Eliminating password protections for invoice processing
- [ ] Centralizing all purchasing and payment authority in one person

> **Explanation:** Segregating duties reduces the opportunity for a single individual to perpetrate and conceal fraudulent transactions.  

### What might be indicated by a sharp decrease in days payable outstanding (DPO)?

- [x] Early payments to vendors or missing payables
- [ ] Lower cost of goods sold ratio
- [ ] Longer payroll cycles
- [ ] Decreased cash flow

> **Explanation:** A dramatic decrease in DPO might be caused by paying invoices sooner than usual or not recording payables. Both scenarios can create financial distortions.  

### In an audit of payroll, the practice of comparing wage rates in the payroll records to authorized rates in HR documentation ensures:

- [x] True
- [ ] False

> **Explanation:** This is a valid test that ensures employees are being paid their authorized wages, mitigating the risk of overpayment and fraud.  

{{< /quizdown >}}

--------------------------------------------------------------------------------

## For Additional Practice and Deeper Preparation

**[Auditing & Attestation CPA Mock Exams (AUD): Comprehensive Prep](https://www.udemy.com/course/aud-cpa-mock-exams/?referralCode=D064EF7BD4A84FC6403D)**  
• Tackle full-length mock exams designed to mirror real AUD questions—from risk assessment and ethics to internal control and substantive procedures.  
• Refine your exam-day strategies with detailed, step-by-step solutions for every scenario.  
• Explore in-depth rationales that reinforce understanding of higher-level concepts, giving you a decisive edge on test day.  
• Boost confidence and reduce exam anxiety by building mastery of the wide-ranging AUD blueprint.

_Disclaimer: This course is not endorsed by or affiliated with the AICPA, NASBA, or any official CPA Examination authority. All content is created solely for educational and preparatory purposes._

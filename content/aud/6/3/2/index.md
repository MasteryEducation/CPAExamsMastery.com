---
title: "Example Opinion Scenarios: Comprehensive Insights for CPA Candidates"
description: "Explore illustrative auditor's report scenarios, detailing clean opinions with emphasis-of-matter, qualified opinions, disclaimers, and adverse opinions. Understand key triggers, materiality thresholds, and proper language usage aligned with AU-C Section 705 and PCAOB AS 3101/3105."
linkTitle: "C.2 Example Opinion Scenarios"
date: 2025-02-07
type: docs
nav_weight: 3102
license: "© 2024 Tokenizer Inc. CC BY-NC-SA 4.0"
---

## C.2 Example Opinion Scenarios

In the journey toward mastering audit reports, it is essential to understand how different opinion scenarios arise and how each report reflects an auditor’s judgment of an entity’s financial statements. This section showcases four main outcomes under Generally Accepted Auditing Standards (GAAS) and Public Company Accounting Oversight Board (PCAOB) standards:

1. Clean (Unmodified) Opinion with an Emphasis-of-Matter Paragraph  
2. Qualified Opinion  
3. Disclaimer of Opinion  
4. Adverse Opinion  

We will also review fundamental terminology and reference the relevant professional standards governing modifications to an auditor’s opinion, including AU-C Section 705 “Modifications to the Opinion in the Independent Auditor’s Report” (AICPA) and PCAOB Auditing Standards 3101 and 3105 (for issuers).

-------------------------------------------------------------------------------

### Overview of Modified Opinions

To help visualize the decision framework that auditors follow when deciding which opinion to issue, consider the decision tree below. It outlines how an auditor moves from unmodified or “clean” opinions to modifications (Qualified, Adverse, or Disclaimer) based on the nature and extent of misstatements or scope limitations:

```mermaid
flowchart TB
    A((Start)) --> B{Material Misstatement<br>or Scope Limitation?}
    B -- No --> C[Unmodified Opinion<br>(Possible Emphasis-of-Matter)]
    B -- Yes --> D{Material <br>or Material & Pervasive?}

    D -- Material but Not Pervasive --> E[Qualified Opinion]
    D -- Material & Pervasive --> F{Misstatement or Scope Limitation?}

    F -- Misstatement --> G[Adverse Opinion]
    F -- Scope Limitation --> H[Disclaimer of Opinion]
```

• “Material” refers to the significance of the error or omission.  
• “Pervasive” means the effects of the misstatement or limitation are so widespread that they impact multiple financial statement elements or fundamentally undermine reliance on the statements.

-------------------------------------------------------------------------------

## 1. Clean (Unmodified) Opinion with Emphasis-of-Matter Paragraph

### 1.1 When and Why It Arises
An unmodified (clean) opinion states that the financial statements present fairly, in all material respects, the financial position and results of the entity’s operations according to the applicable financial reporting framework (e.g., U.S. GAAP). However, auditors sometimes add an Emphasis-of-Matter (EoM) paragraph to highlight a specific issue without modifying their overall opinion.

Common reasons for issuing an unmodified opinion with an EoM paragraph include:  
• Significant subsequent events (for instance, a natural disaster occurring after the financial year-end but disclosed properly).  
• Changes in accounting principles that materially affect comparability but have been appropriately disclosed.  
• Unusual important transactions, uncertainties, or contingencies that the auditor wishes to emphasize.

### 1.2 Illustrative Example
Below is an illustrative (condensed) excerpt from an independent auditor’s report with an EoM paragraph related to a change in accounting principle:

-------------------------------------------------------------------------
INDEPENDENT AUDITOR’S REPORT

We have audited the accompanying financial statements of XYZ Corporation, which comprise… [standard unmodified opinion introduction and basis for opinion sections]…

In our opinion, the financial statements referred to above present fairly, in all material respects, the financial position of XYZ Corporation as of December 31, 20XX, and the results of its operations and its cash flows for the year then ended in accordance with accounting principles generally accepted in the United States of America.

Emphasis of Matter  
As discussed in Note X to the financial statements, during 20XX, the Company adopted Accounting Standards Update (ASU) 20XX-XX, which represents a change from the method previously used. Our opinion is not modified with respect to this matter.

[Signature of the auditor]  
[Auditor’s address]  
[Date of the audit report]

-------------------------------------------------------------------------

### 1.3 Practical Considerations
• Ensure the EoM paragraph is placed immediately after the Opinion section.  
• Clearly reference the note in the financial statements describing the event or change in principle.  
• State that the auditor’s opinion is not modified with respect to the matter discussed.

-------------------------------------------------------------------------------

## 2. Qualified Opinion

### 2.1 When and Why It Arises
A qualified opinion is issued when one of the following occurs:  
• A material misstatement is present in a specific account or disclosure, but it is not pervasive—often described as “except for” the described matter, the financial statements are presented fairly.  
• The auditor was unable to obtain sufficient appropriate audit evidence for one element or area, but this limitation does not affect the entirety of the financial statements.

If the misstatement or scope limitation is isolated to a particular section or does not overshadow the overall fairness of the financial statements, a qualified opinion may be appropriate.

### 2.2 Language and Format
Under GAAS (AU-C Section 705) and PCAOB standards (AS 3101/3105), the wording of a qualified opinion typically includes the phrase “except for the effects of the matter described in the Basis for Qualified Opinion section, the financial statements present fairly…”

### 2.3 Illustrative Example (Material Misstatement)
-------------------------------------------------------------------------
INDEPENDENT AUDITOR’S REPORT

Basis for Qualified Opinion  
We conducted our audit in accordance with GAAS… [include standard language about responsibilities]. However, the Company has recorded its inventory at cost, which Management has not adjusted for net realizable value. Management’s calculation and supporting documentation indicate that approximately $1 million in inventory losses have not been accounted for in the accompanying financial statements.

Qualified Opinion  
In our opinion, except for the effects of the matter discussed in the Basis for Qualified Opinion section, the financial statements referred to above present fairly, in all material respects, the financial position of ABC Corporation…

[Signature of the auditor]  
[Auditor’s address]  
[Date of the audit report]

-------------------------------------------------------------------------

### 2.4 Practical Considerations
• Clearly describe the specific issue leading to the qualification in the “Basis for Qualified Opinion” section.  
• Use “except for” language to isolate the problematic area.  
• Include an estimate or quantification of the misstatement whenever possible.

-------------------------------------------------------------------------------

## 3. Disclaimer of Opinion

### 3.1 When and Why It Arises
A disclaimer of opinion is issued when the auditor cannot form an opinion due to severe scope limitations. In other words, the auditor was unable to obtain sufficient evidence to support an opinion. Situations leading to disclaimers may include:

• The client’s records are missing or significantly incomplete, making verification impossible.  
• Restrictions imposed by management or circumstances preventing essential audit procedures.  
• Pervasive uncertainty that makes forming a conclusion impossible (not merely because management used an unusual accounting principle, but because the auditor cannot verify critical supporting data).

### 3.2 Illustrative Example
-------------------------------------------------------------------------
INDEPENDENT AUDITOR’S REPORT

Disclaimer of Opinion  
We were engaged to audit the accompanying financial statements of DEF Company as of and for the year ended December 31, 20XX. We could not obtain sufficient appropriate audit evidence regarding the Company’s revenue transactions because management did not provide access to relevant customer invoices and sales contracts.

Because of the significance of the matter described in the Basis for Disclaimer of Opinion section, we were not able to obtain sufficient appropriate audit evidence to provide a basis for an audit opinion. Accordingly, we do not express an opinion on these financial statements.

Basis for Disclaimer of Opinion  
We conducted our engagement in accordance with GAAS… [continue standard required disclaimers and language].

[Signature of the auditor]  
[Auditor’s address]  
[Date of the audit report]

-------------------------------------------------------------------------

### 3.3 Practical Considerations
• Use the heading “Disclaimer of Opinion” instead of “Opinion.”  
• Avoid describing the results of any procedures because the overall inability to gather critical evidence renders all results inconclusive.  
• Though the reasons are typically explained immediately after the disclaimer, the overall tone should convey that the auditor cannot opine—rather than “the statements are wrong,” it communicates “we cannot determine whether the statements are correct.”

-------------------------------------------------------------------------------

## 4. Adverse Opinion

### 4.1 When and Why It Arises
An adverse opinion is the most critical type of modified opinion. It states that the financial statements do not present fairly the financial position or results of the entity due to a material misstatement that is also pervasive. Typical triggers:

• The entity’s use of fundamentally incorrect accounting policies that affect multiple items in the financial statements.  
• Multiple material misstatements or significant non-compliance with GAAP rendering the financial statements misleading overall.  

### 4.2 Illustrative Example
-------------------------------------------------------------------------
INDEPENDENT AUDITOR’S REPORT

Adverse Opinion  
We have audited the accompanying financial statements of GHI Corporation. In our opinion, because of the significance of the matters discussed in the Basis for Adverse Opinion section, the financial statements do not present fairly the financial position of GHI Corporation as of December 31, 20XX, or the results of its operations and its cash flows for the year then ended, in accordance with accounting principles generally accepted in the United States of America.

Basis for Adverse Opinion  
Management has failed to consolidate a wholly-owned subsidiary in accordance with U.S. GAAP. Additionally, a material portion of intangible assets is overstated due to the omission of required impairment testing. As a result, the financial statements are materially misstated, and the misstatement is pervasive to assets, liabilities, and net income.

[Signature of the auditor]  
[Auditor’s address]  
[Date of the audit report]

-------------------------------------------------------------------------

### 4.3 Practical Considerations
• Clearly articulate the reasons for the adverse opinion in the “Basis for Adverse Opinion” section.  
• Provide insight into how the misstatement is pervasive, impacting multiple statements or fundamentally undermining the reliability of the financial statements.

-------------------------------------------------------------------------------

## 5. Key Terminology Reference

Below are select terms that guide auditors in choosing the appropriate opinion type:

• **Except for**: Language used in a qualified opinion to isolate the specific area of misstatement or limitation.  
• **Material and Pervasive**: Level of seriousness and breadth of a misstatement or limitation. If both conditions are met, an adverse or disclaimer of opinion is warranted depending on whether the issue is a misstatement or lack of evidence.  
• **Scope Limitation**: A limitation on the auditor’s ability to gather sufficient appropriate evidence. This might be due to physical constraints, unavailability of documents, or restrictions by management.

-------------------------------------------------------------------------------

## 6. References and Further Reading

• AU-C Section 705: “Modifications to the Opinion in the Independent Auditor’s Report.”  
• PCAOB AS 3101: “The Auditor’s Report on an Audit of Financial Statements When the Auditor Expresses an Unqualified Opinion.”  
• PCAOB AS 3105: “Departures from Unqualified Opinions and Other Reporting Circumstances.”  
• AICPA Professional Standards: For the full text of authoritative guidance.  
• GAAS Hierarchy: Outlines how GAAS is structured, which standards are binding, and which are interpretative.  

-------------------------------------------------------------------------------

## Advanced Auditor Opinion Scenario Quiz for CPA Candidates

{{< quizdown >}}

### Which type of auditor's opinion states that the financial statements comport with GAAP, yet highlights a particular matter without modifying the overall opinion?  
- [x] Unmodified opinion with an Emphasis-of-Matter paragraph  
- [ ] Qualified opinion  
- [ ] Adverse opinion  
- [ ] Disclaimer of opinion  

> **Explanation:** An emphasis-of-matter paragraph is used when the auditor deems it necessary to call attention to a specific issue (e.g., a change in accounting principle), but the issue does not affect the overall fairness of the statements.

### Which standard provides guidance for modifying an auditor’s opinion under GAAS for non-issuers?  
- [ ] PCAOB AS 3101  
- [x] AU-C Section 705  
- [ ] SAS 99  
- [ ] AICPA AP 310  

> **Explanation:** AICPA AU-C Section 705, titled “Modifications to the Opinion in the Independent Auditor’s Report,” specifically addresses when and how to modify opinions under GAAS.

### Under what circumstances would an auditor most likely issue a disclaimer of opinion?  
- [x] When the auditor cannot obtain sufficient appropriate evidence due to a significant scope limitation  
- [ ] When the financial statements have an isolated material misstatement  
- [ ] When the financial statements are fairly presented, except for a minor omission  
- [ ] When the auditor believes the financial statements do not fairly present the entity’s financial position  

> **Explanation:** A disclaimer is issued when the auditor is unable to express an opinion, typically from severe scope limitations or lack of access to sufficient evidence.

### Pervasive misstatements that significantly distort the overall financial statements generally result in which type of opinion?  
- [ ] Unmodified  
- [ ] Qualified  
- [ ] Disclaimer  
- [x] Adverse  

> **Explanation:** An adverse opinion is issued when misstatements are both material and pervasive, rendering the financial statements not fairly presented as a whole.

### When issuing a qualified opinion for a material misstatement, what is the most common phrase used in the opinion paragraph?  
- [ ] “We do not express an opinion…”  
- [ ] “The financial statements do not present fairly…”  
- [x] “Except for the effects of the matter described…”  
- [ ] “We express our adverse opinion…”  

> **Explanation:** “Except for the effects of the matter described…” is standard phrasing in a qualified opinion to isolate the misstatement from the rest of the financial statements.

### An emphasis-of-matter paragraph is added to:  
- [x] Highlight a change in accounting principle or subsequent event while remaining unmodified  
- [ ] Express disagreement with management’s policies  
- [ ] Disclose a material scope limitation  
- [ ] Force management to restate their financials  

> **Explanation:** An emphasis-of-matter paragraph shines a spotlight on a crucial issue for readers. It does not alter the unmodified opinion but adds further clarity on the matter.

### What is one key difference between a disclaimer of opinion and an adverse opinion?  
- [x] A disclaimer results from insufficient evidence; an adverse results from identified, pervasive misstatements  
- [ ] Both disclaimers and adverse opinions state “financial statements are reliable.”  
- [ ] An adverse opinion is used for scope limitations, while a disclaimer covers incorrect accounting principles.  
- [ ] There is no distinction, both mean the same thing.  

> **Explanation:** Disclaimers are due to a lack of sufficient evidence, while adverse opinions occur when evidence shows material and pervasive misstatements.

### Which paragraph of the audit report addresses the specific misstatement or limitation when issuing a modified opinion?  
- [ ] Opinion Paragraph  
- [x] Basis for Opinion (or Basis for Qualified/Adverse/Disclaimer)  
- [ ] Auditor’s Responsibilities Paragraph  
- [ ] Management’s Responsibilities Paragraph  

> **Explanation:** Auditors must detail the nature of the problem in the Basis for Opinion section, laying out the reason behind the modification.

### If a single account is misstated but does not significantly impact the overall financial statements, which opinion is usually most appropriate?  
- [ ] Adverse Opinion  
- [ ] Disclaimer of Opinion  
- [ ] Unmodified Opinion with Emphasis-of-Matter  
- [x] Qualified Opinion  

> **Explanation:** A single, isolated misstatement that is material but not pervasive typically leads to a qualified opinion.

### True or False: After issuing a disclaimer of opinion, the auditor should provide detailed findings on individual account balances in the report.  
- [x] True  
- [ ] False  

> **Explanation:** Although disclaimers mean “no opinion” on the statements as a whole, the auditor may still indicate if certain items were verified. However, the key premise is that the overall limitation prevents forming an opinion on the financial statements. The prevalent convention is to keep disclaimers succinct, but some modern practices allow limited findings to be disclosed. Always consult professional standards for nuanced guidance.

{{< /quizdown >}}

-------------------------------------------------------------------------------

## For Additional Practice and Deeper Preparation

**[Auditing & Attestation CPA Mock Exams (AUD): Comprehensive Prep](https://www.udemy.com/course/aud-cpa-mock-exams/?referralCode=D064EF7BD4A84FC6403D)**  
• Tackle full-length mock exams designed to mirror real AUD questions—from risk assessment and ethics to internal control and substantive procedures.  
• Refine your exam-day strategies with detailed, step-by-step solutions for every scenario.  
• Explore in-depth rationales that reinforce understanding of higher-level concepts, giving you a decisive edge on test day.  
• Boost confidence and reduce exam anxiety by building mastery of the wide-ranging AUD blueprint.

_Disclaimer: This course is not endorsed by or affiliated with the AICPA, NASBA, or any official CPA Examination authority. All content is created solely for educational and preparatory purposes._

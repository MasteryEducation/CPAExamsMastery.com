---
title: "Impact on Financial Statements vs. Notes Disclosure"
description: "Understand the pivotal difference between recognized (adjusting) and nonrecognized (disclosure-only) subsequent events. Learn how each type impacts financial statements, discover best practices, and avoid common pitfalls."
linkTitle: "24.3 Impact on Financial Statements vs. Notes Disclosure"
date: 2025-02-07
type: docs
nav_weight: 6430
license: "© 2024 Tokenizer Inc. CC BY-NC-SA 4.0"
---

## 24.3 Impact on Financial Statements vs. Notes Disclosure

Subsequent events can significantly affect the way financial statements are prepared and presented. In practice, an event that occurs between the balance sheet date and the date the financial statements are available to be issued (or “issued” in the case of public companies) can either require a direct adjustment to the financial statements or a disclosure in the notes. This distinction is crucial because it ensures that users of financial statements have accurate and relevant information about conditions existing at period-end and events arising after that date. In this section, we will explore the types of subsequent events, how they affect the financials, and the principles that guide whether such events are recognized through adjusting entries or disclosed in the notes.

---

## Key Definitions and Overview of Subsequent Events

When we talk about subsequent events in the context of U.S. GAAP, we generally rely on Accounting Standards Codification (ASC) Topic 855, “Subsequent Events.” IFRS has a parallel concept under IAS 10, “Events After the Reporting Period,” commonly referred to as “adjusting” versus “non-adjusting” events. Regardless of the framework, the core idea is the same: to determine which events should shape the reported financial results and which should only be disclosed in the notes.

1. Subsequent Event: Any event or transaction that occurs after the balance sheet date but before the financial statements are either issued or available to be issued.  
2. Recognized (Adjusting) Event: Provides additional evidence about conditions that existed at the balance sheet date, thus requiring an adjustment to the financial statements.  
3. Nonrecognized (Disclosure-Only) Event: Relates to conditions that arose after the balance sheet date, thus not requiring an adjustment to the financials but often requiring disclosure to ensure users are informed about significant developments.

---

## Recognized Events (Adjusting Entries)

Recognized subsequent events (sometimes called “Type 1 events”) reflect information about conditions that existed on or before the balance sheet date. Because they provide evidence regarding the estimate of an asset’s or liability’s value as of period-end, they must be incorporated into the financial statements through adjusting entries.

### Characteristics of Recognized Events

• They concern conditions that were present at the balance sheet date.  
• They often involve refinements or clarifications of estimates made prior to period-end—for example, the final determination of litigation, the receipt of new information on uncertain accounts receivable, or updated inventory data.  
• They change the estimates on which the financial statements are based.  

### Common Examples

1. A major customer’s bankruptcy that confirms the customer’s financial difficulty as of the balance sheet date. This scenario typically requires writing down or writing off the related receivable if it becomes apparent the customer would not have been able to pay its debts at year-end.  
2. Settlement of litigation that was ongoing at the balance sheet date. If the company was already involved in a lawsuit and preliminary findings suggest the event was in process at period-end, any settlement amount should be reflected in the financial statements.  
3. Additional discoveries about inventory on hand at reporting date—such as hidden merchandise or damage—that existed prior to period-end but was only uncovered afterward.

### Journal Entry Illustration

Imagine a company had a receivable of $100,000 from a client at year-end. Subsequent to the balance sheet date (but before issuance of the statements), the client files for bankruptcy. Evidence shows the financial difficulties existed prior to year-end, although the bankruptcy filing occurred shortly thereafter. The adjusting journal entry might look like this:

Dr. Bad Debt Expense ………. $100,000  
Cr. Allowance for Doubtful Accounts … $100,000  

This entry ensures the updated financial statements accurately reflect the collectibility risk at the balance sheet date.

---

## Nonrecognized Events (Disclosure Only)

Nonrecognized subsequent events (often called “Type 2 events”) arise from conditions that did not exist at the balance sheet date; rather, they arose after that date. In these instances, the financial statements are not adjusted, but disclosure is typically required if failure to do so would mislead financial statement users.

### Characteristics of Nonrecognized Events

• They typically reveal new conditions (e.g., a terrorist attack damaging company assets after period-end, or a major acquisition contract entered into after year-end).  
• Financial statement amounts remain unchanged.  
• Adequate disclosure in the footnotes is necessary if the impact on the company is material and knowledge of the event is essential for users.

### Common Examples

1. A fire in a warehouse occurring after year-end that destroys inventory. If this loss was not foreseeable at the balance sheet date, no adjustment is made to the year-end inventory value. However, a note may be included to inform readers about the event and any estimated financial impact or insurance coverage.  
2. Issuance of significant equity or debt securities after year-end but before the statements are issued.  
3. Business combination or major financing arrangement closing after period-end.  
4. Decline in fair value of investments after the balance sheet date due to market volatility arising from events that occurred subsequent to the reporting date.  

### Disclosure-Only Illustration

If a company invests heavily in specialized equipment after year-end and the transaction is large enough to influence a user’s understanding of the business, it should disclose, for example:

“On February 10, 20XX, the Company acquired advanced manufacturing equipment for total consideration of $2.5 million. Management expects the new equipment to significantly improve production efficiency and expand manufacturing capacity. No adjustments to the December 31, 20XX, financial statements have been made since the purchase was completed after that date.”

---

## Significant Judgments: Evaluating the Need for Adjusting Entries or Disclosure

Determining whether an event is recognized or nonrecognized often requires significant professional judgment. Management must assess:

1. **Nature and Timing of the Event**  
   – Did the event indicate a preexisting condition as of the balance sheet date?  
   – Or was it triggered by circumstances arising fully after that date?

2. **Materiality**  
   – Would omitting or misstating either the adjustment or the disclosure be likely to influence users’ decisions?  

3. **Legal Considerations**  
   – Potential confidentiality agreements or ongoing negotiations might affect the wording of disclosures, but do not remove the need to disclose.

4. **Communication with Auditors**  
   – Subsequent events are frequently a key audit point. Auditors request legal letters and internal confirmations to verify major post-balance sheet events.

---

## Visualizing the Subsequent Events Decision Process

Below is a Mermaid.js diagram that summarizes the decision flow for determining whether to adjust or disclose:

```mermaid
flowchart TB
    A([End of Reporting Period]) --> B{Event Occurs\\After Reporting Date?}
    B -- Yes --> C(Is the condition\\related to prior year end?)
    B -- No --> D[No subsequent event\\treatment required]
    C -- Yes --> E[Recognized Event\\\(Adjust FS)]
    C -- No --> F[Nonrecognized Event\\\(Disclosure Only)]
    E --> G([Issue Financial\\Statements])
    F --> G
```

Explanation of Diagram:  
• If the condition existed at the reporting date, record an adjusting entry and revise the financial statements.  
• If the condition arose after the reporting date and did not exist before, disclosure is typically required if the event is significant. Otherwise, no subsequent event treatment is needed.

---

## Best Practices and Common Pitfalls

### Best Practices

• **Establish a Formal Review Process**  
  – Create a clear “cutoff” after the balance sheet date and regularly check for significant events that could affect financial statements.

• **Collaborate with Legal Advisors**  
  – Subsequent events often involve legal cases or contingencies. Involving legal counsel helps ensure that potential amounts or liabilities are spotted in time.

• **Transparent Disclosure**  
  – Even if an event is nonrecognized, clarity in written footnotes about timing, nature, and potential financial effect is critical.  

• **Use of an Event Log**  
  – Document every major event happening after year-end (mergers, capital raises, large capital expenditures), then evaluate them systematically.

### Common Pitfalls

• **Failing to Identify an Ongoing Risk at Year-end**  
  – Companies may not realize a recognized subsequent event if they only consider documents signed after year-end. The underlying condition could have existed earlier.

• **Inadequate Disclosures**  
  – Understating the significance of a major acquisition or ignoring it altogether can mislead readers.  

• **Overlooking Nonrecognized Events**  
  – Dismissing a post-reporting event without considering its future implications can leave financial statement users uninformed.  

• **Cutoff Confusion**  
  – Some events may straddle the barrier between recognized and nonrecognized. Clear articulation and documentation are essential for making the right call.

---

## Real-World Case Studies

1. **Bankruptcy Filing Reveals Preexisting Conditions**  
   A small manufacturing company had been receiving late payments from a major customer. The audit team requested updates regarding this customer’s solvency. One week after the balance sheet date, the customer declared bankruptcy. Evidence indicated the customer had been insolvent for months, so the event was recognized, and the manufacturing company recorded an allowance for uncollectible receivables.  

2. **Scroll-Tech Acquisition**  
   Scroll-Tech, a tech startup, was acquired by a large conglomerate 10 days after year-end. Negotiations began well after the balance sheet date, with no prior indications. Because the condition (the merger offering) did not exist at year-end, it was deemed a nonrecognized event. Management included a note to highlight the acquisition in the financial statements, especially as it would significantly alter the company’s financial outlook.  

3. **Fire at a Warehouse Days After Year-End**  
   A distribution company stored most of its inventory in a single warehouse. On December 31, the inventory was intact and in good condition. However, on January 3, a fire devastated the warehouse. The inventory was uninsured. Because the fire happened after the balance sheet date and was unrelated to conditions existing at year-end, the financial statements were not adjusted. However, a detailed secondary note was included to inform investors of the potential impact on future operations and the financial position.

---

## IFRS Considerations

Under IFRS (IAS 10), subsequent events are split into “adjusting events” and “non-adjusting events,” which closely align with the recognized and nonrecognized events in U.S. GAAP. Adjusting events under IFRS provide evidence of conditions that existed at the end of the reporting period, leading to an adjustment in the financial statements. Non-adjusting events are those indicative of conditions that arose after the reporting period, thus disclosed but not recognized.

Key differences typically include the precise terminology and certain definitions regarding what might constitute a “condition” at the reporting date. However, the overall concept is consistent across IFRS and U.S. GAAP.

---

## Comprehensive Table: Recognized vs. Nonrecognized

Below is a summary table contrasting recognized (adjusting) and nonrecognized (disclosure-only) subsequent events:

|               | Recognized (Adjusting) Event                   | Nonrecognized (Disclosure-Only) Event                               |
|---------------|-----------------------------------------------|---------------------------------------------------------------------|
| **Definition**     | Occurs after year-end but provides additional evidence about conditions that existed at the balance sheet date. | Occurs after year-end and relates to new conditions that did not exist at the balance sheet date. |
| **Accounting Treatment**  | Record adjusting entry in the financial statements.                       | Add footnote disclosure if the event is significant and material.  |
| **Examples**    | Bankruptcy of a major customer that was insolvent at year-end; settlement of pre-existing litigation.  | Stock issuance after year-end for expansion; major disaster destroying inventory after year-end. |
| **Impact on Financials**  | Changes reported amounts or classifications.                              | No direct changes in recognized amounts, but ensures transparency for users.          |
| **Reference**   | U.S. GAAP: ASC 855; IFRS: IAS 10 (Adjusting events).                            | U.S. GAAP: ASC 855; IFRS: IAS 10 (Non-adjusting events).                          |

---

## Practical Guidance for Preparers and Auditors

1. **Stay Alert During the Subsequent Events Period**  
   Conduct regular meetings with department heads and legal counsel in the weeks following year-end to keep a pulse on any developments.

2. **Maintain Consistency with Prior Periods**  
   If a certain category of transaction was previously deemed recognized, a shift to disclosure-only (or vice versa) warrants a coherent explanation.

3. **Consultation with External Experts**  
   Complex situations, such as catastrophic environmental damage or massive litigation, may require outside expertise to gauge timing and potential financial impact accurately.

4. **Create a Timeline**  
   Mark the date the financial statements are expected to be issued or available to be issued. Map all major events and their relevant facts along this timeline, noting especially which conditions existed at year-end versus which arose later.

5. **Cross-Reference with Other Parts of the Financial Statements**  
   For significant subsequent events, ensure the disclosures match with or reference any relevant management discussion and analysis (MD&A) for public companies, or additional required supplementary information (RSI) in governmental reporting, as discussed in Chapter 5 of this guide.

---

## Additional Resources

• FASB ASC 855 – “Subsequent Events”  
• IFRS IAS 10 – “Events After the Reporting Period”  
• AICPA Audit Guide – Guidance on the role of auditors in identifying and evaluating subsequent events  
• COSO’s Enterprise Risk Management Framework – Helpful for designing robust internal controls that spot subsequent event triggers proactively  

---

## SEO-Optimized Quiz: Test Your Knowledge of Adjusting Entries & Disclosures

{{< quizdown >}}

### Which of the following best describes a recognized (adjusting) subsequent event?

- [x] It provides evidence of a condition existing at the balance sheet date.
- [ ] It relates only to events occurring entirely after the reporting period without any preexisting conditions.
- [ ] It never impacts the financial statements themselves, only the notes.
- [ ] It is always immaterial and thus excluded from any footnote descriptions.

> **Explanation:** Recognized events offer evidence that a condition existed at or before the balance sheet date, requiring an adjustment to reflect the true financial position and performance.

### Which scenario is most likely to be treated as nonrecognized (disclosure-only) under GAAP?

- [ ] A major supplier’s insolvency known to be long-standing at the year-end date.
- [x] A factory fire occurring two weeks after year-end, destroying inventory previously in good condition.
- [ ] Change in the estimate of depreciation due to new information about the asset’s condition at year-end.
- [ ] Revaluation of an already identified litigation settlement before the statements are issued.

> **Explanation:** A factory fire taking place after the reporting period and not related to preexisting conditions is typically disclosed rather than recognized.

### When should a footnote disclosure be provided for a nonrecognized subsequent event?

- [x] When the event is material and knowledge of the event is necessary for readers to understand the financial condition or performance.
- [ ] Anytime there is a post-reporting date transaction, regardless of materiality.
- [ ] Only if the event affects stockholders’ equity.
- [ ] Never, as nonrecognized events do not alter the financial statements.

> **Explanation:** Disclosure is required if the subsequent event is so significant that its absence would mislead readers or alter their decisions about the entity.

### In accounting terminology, which of the following is a recognized subsequent event under IFRS?

- [x] “Adjusting event” that provides evidence of conditions present at the end of the reporting period.
- [ ] “Adjusting event” that only arises entirely after the reporting period.
- [ ] “Non-adjusting event” that indicates new conditions developed after year-end.
- [ ] Event discovered after the date the financial statements have been issued.

> **Explanation:** IFRS uses the term “adjusting event” to refer to events that confirm conditions existing at the period-end.

### What is the usual accounting treatment for a recognized (adjusting) subsequent event?

- [x] An adjusting journal entry is recorded before issuing the statements, updating the amounts and presentation if needed.
- [ ] A separate pro forma statement is prepared instead of adjusting the original financials.
- [x] A footnote disclosure is optional in this scenario.
- [ ] The event is entirely ignored if it becomes known after the audit begins.

> **Explanation:** Recognized events typically result in an adjusting journal entry as they confirm conditions existing at year-end, and management can optionally include additional footnote details for clarity.

### A company reaches a large settlement for a lawsuit that was ongoing at year-end. Which approach is most appropriate?

- [x] Record the settlement amount in the financial statements if the lawsuit indicates conditions preexisting year-end.
- [ ] Disclose only, as it is always considered nonrecognized.
- [ ] Never mention the lawsuit due to confidentiality restrictions.
- [ ] Record the settlement if a final check to the plaintiff is sent before issuance, regardless of year-end conditions.

> **Explanation:** If the lawsuit relates to conditions existing at year-end, it’s an adjusting event and must be recognized.

### True or False: All events that occur after year-end and receive media coverage should be recognized in the financial statements.

- [x] False
- [ ] True
- [x] True
- [ ] False

> **Explanation:** Media coverage alone is not a determining factor. The key question is whether the event reflects conditions existing at year-end or arises fully afterward.

### Which of the following can exemplify a Type 2 subsequent event?

- [x] A significant business combination initiated after year-end with no prior negotiations reported at the balance sheet date.
- [ ] A customer’s insolvency known as a risk at the balance sheet date.
- [ ] Revised overhead allocation rates discovered to be inaccurate for the year.
- [ ] A final inventory count performed before the period-end.

> **Explanation:** A business combination commenced wholly after year-end is typically a nonrecognized event, necessitating disclosure if material.

### A fire occurs in a company’s largest factory the day after the reporting date. Which statement is correct?

- [x] The financial statements themselves are not adjusted, but a prominent footnote is often required if the event is material.
- [ ] Both an adjustment and a footnote are always required.
- [ ] No mention is made if the factory was insured.
- [ ] The entity must retroactively adjust inventory balances as of the reporting date.

> **Explanation:** Because the condition did not exist at year-end, no adjustment is made; however, a substantial event such as a destructive fire usually warrants footnote disclosure.

### In which situation should a subsequent event be recognized (rather than disclosed only)?

- [x] The subsequent information reveals conditions that existed at the balance sheet date which affect the reported amounts.
- [ ] The event strictly pertains to brand new conditions arising after the balance sheet date.
- [ ] The event has no material bearing on the company’s financial position or performance.
- [ ] The auditor instructs management not to record it regardless of its nature.

> **Explanation:** Subsequent events that clarify existing conditions at the balance sheet date must be incorporated so that the financial statements remain faithful to reality.

{{< /quizdown >}}

---

## For Additional Practice and Deeper Preparation

**[FAR CPA Hardest Mock Exams: In-Depth & Clear Explanations](https://www.udemy.com/course/far-cpa-mock-exams/?referralCode=F88050F8D5C76764F6BD)**

Financial Accounting and Reporting (FAR) CPA Mocks: 6 Full (1,500 Qs), Harder Than Real! In-Depth & Clear. Crush With Confidence!

- Tackle full-length mock exams designed to mirror real FAR questions.  
- Refine your exam-day strategies with detailed, step-by-step solutions for every scenario.  
- Explore in-depth rationales that reinforce higher-level concepts, giving you an edge on test day.  
- Boost confidence and minimize anxiety by mastering every corner of the FAR blueprint.  
- Perfect for those seeking exceptionally hard mocks and real-world readiness.  

_Disclaimer: This course is not endorsed by or affiliated with the AICPA, NASBA, or any official CPA Examination authority. All content is for educational and preparatory purposes only._
{{< katex />}}


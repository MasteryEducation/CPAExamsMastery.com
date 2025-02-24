---
title: "Depreciation Methods (SL, DDB, Sum-of-the-Years’-Digits), Depletion"
description: "A comprehensive guide exploring Straight-Line, Double-Declining Balance, and Sum-of-the-Years’-Digits depreciation methods, plus depletion for natural resources. Includes formulas, partial-year examples, practical illustrations, visual diagrams, and best practices."
linkTitle: "12.2 Depreciation Methods (SL, DDB, Sum-of-the-Years’-Digits), Depletion"
date: 2025-02-07
type: docs
nav_weight: 4220
license: "© 2024 Tokenizer Inc. CC BY-NC-SA 4.0"
---

## 12.2 Depreciation Methods (SL, DDB, Sum-of-the-Years’-Digits), Depletion

This section provides a thorough exploration of depreciation methods and depletion, as required in Financial Accounting and Reporting (FAR) under U.S. GAAP. The concepts covered apply to both private companies and publicly traded entities, and where relevant, distinctions and notes on International Financial Reporting Standards (IFRS) are highlighted to emphasize convergence efforts and key policy differences.

Depreciation is the systematic allocation of the cost of a tangible fixed asset over its estimated useful life, reflecting how the asset’s economic benefits are consumed. Different methods serve different usage patterns, ensuring that expenses match revenue generation and reflect economic reality. Depletion follows similar conventions but pertains specifically to natural resources (e.g., minerals, oil, timber) whose value diminishes as the resource is extracted or consumed.

This section breaks down:
• Core depreciation methods (Straight-Line, Double-Declining Balance, and Sum-of-the-Years’-Digits)  
• Partial-year depreciation approaches  
• Depletion for natural resources  

---

### Overview and Importance of Depreciation Selection

Selecting the appropriate depreciation method is often a matter of judgment, guided by management’s estimate of how an asset is used. Under both U.S. GAAP and IFRS, companies are encouraged to review depreciation methods regularly to ensure the method chosen accurately matches the pattern of economic benefit realization.

Key considerations for choosing a depreciation method include:
• Expected usage or wear-and-tear of the asset  
• Technology or market changes that may obsolesce an asset  
• Financial reporting objectives and matching principles  
• Industry practices and regulatory requirements  

Common pitfalls:
• Underestimating or overestimating the asset’s useful life can distort financial statements.  
• Failing to consider salvage (residual) value accurately may lead to misstatement of depreciation expense.  
• Omitting partial-year conventions can cause inaccuracies in the first and last year of an asset’s use.  

---

### Straight-Line (SL) Method

The Straight-Line (SL) method is the simplest and most commonly applied. It evenly allocates the asset’s depreciable base—calculated as the asset’s cost minus its salvage (residual) value—over the asset’s estimated useful life.

#### Formula

Let:
• C = Asset cost  
• S = Salvage (residual) value  
• n = Useful life (in years)  

Then, annual depreciation expense under the SL method is:

{{< katex >}}
\text{Annual Depreciation} = \frac{C - S}{n}
{{< /katex >}}

#### Usage Pattern

Straight-Line depreciation is best suited for assets whose benefit to the company remains relatively consistent year-to-year. Examples include office furniture, machinery operating at a constant rate, or buildings used evenly over time.

#### Partial-Year Depreciation Under Straight-Line

There are multiple approaches to partial-year depreciation, including:
1. Pro-Rata by Month (e.g., if an asset is purchased in March, only record depreciation for 10 months of that year).  
2. Half-Year Convention (assume half a year’s depreciation is recognized in both the first and last years).  

Example (Pro-Rata by Month):
• A piece of equipment is acquired on April 1 (start of the second quarter).  
• Asset Cost (C) = \$100,000, Salvage (S) = \$10,000, Estimated Life (n) = 5 years.  
• Annual depreciation without partial-year adjustment = (100,000 – 10,000) ÷ 5 = \$18,000.  
• Because it is in service for 9 months during the first year (April through December), year 1 depreciation would be (9/12) × \$18,000 = \$13,500 under a straightforward monthly allocation.  

---

### Double-Declining Balance (DDB) Method

The Double-Declining Balance (DDB) method accelerates depreciation early in the asset’s useful life. This method is commonly used for assets that lose value quickly in the initial years, such as certain technology-based fixed assets.

#### Formula

Using double the Straight-Line rate (i.e., 2 ÷ n) applied to the asset’s beginning Net Book Value (NBV) each year:

{{< katex >}}
\text{Depreciation for each year} = \left(\frac{2}{n}\right) \times \text{NBV at the beginning of that year}
{{< /katex >}}

NBV at the beginning of the first year = Cost (since no depreciation has yet been taken). Each subsequent year, NBV is reduced by the prior year’s depreciation.

As the method is an accelerated approach, one must monitor salvage value; ensure total depreciation never reduces the net book value below salvage value.

#### Usage Pattern

DDB is suitable for assets whose productivity significantly declines in later years or that become technologically outdated quickly.

#### Partial-Year Depreciation Under DDB

When an asset is purchased partway through a year:
1. Compute the annual depreciation.
2. Apply the half-year or pro-rata convention consistent with the entity’s policy.
3. Recompute the NBV for each subsequent year as a basis for the new depreciation calculation.

Example (Half-Year Convention for First Year):
• Equipment cost = \$80,000, Salvage value = \$5,000, Useful life = 5 years.  
• DDB rate = 2 ÷ 5 = 40%.  
• Year 1 depreciation if a full year: 40% × \$80,000 = \$32,000. With a half-year convention, only \$16,000 is recognized for the first year.  
• NBV at the end of Year 1 = \$80,000 – \$16,000 = \$64,000.  

---

### Sum-of-the-Years’-Digits (SYD) Method

Sum-of-the-Years’-Digits (SYD) is another accelerated method. Unlike DDB, which applies a constant rate to the declining NBV, SYD allocates the asset’s depreciable base more quickly in early years via fractional multipliers.

#### Formula

For an asset with a useful life of n years, the sum of integers from 1 to n (referred to as the “denominator”) is:
{{< katex >}}
\text{Sum of years} = \frac{n(n+1)}{2}
{{< /katex >}}

In year t (t = 1 being the first year, t = 2 the second, etc.), the fraction used to determine depreciation expense is:
{{< katex >}}
\frac{\text{(n – t + 1)}}{\frac{n(n+1)}{2}} 
{{< /katex >}}

Multiplying this fraction by (C – S) gives the depreciation for year t.

Alternatively, some prefer to list out each year’s fraction:

• Year 1 fraction = n ÷ [n(n+1)/2]  
• Year 2 fraction = (n – 1) ÷ [n(n+1)/2]  
• …  
• Year n fraction = 1 ÷ [n(n+1)/2]  

Because each subsequent year the multiplier in the numerator decreases, depreciation expense declines over the asset’s life.

#### Usage Pattern

SYD is useful when an asset’s peak utility is in its earlier years, but the acceleration pattern is less aggressive than DDB in the later years. Large equipment in certain manufacturing contexts can benefit from SYD if it sees heavier use initially.

#### Example

• Cost (C) = \$100,000, Salvage (S) = \$10,000, n = 5 years.  
• Sum of years = 1+2+3+4+5 = 15.  
• Year 1 fraction: 5/15.  
• Year 1 depreciation = (5/15) × (100,000 – 10,000) = (5/15) × 90,000 = \$30,000.  
• Year 2 fraction: 4/15, so Year 2 depreciation = (4/15) × 90,000 = \$24,000, and so on.  

---

### Depletion

Depletion is the systematic allocation of the cost of natural resources (e.g., mineral deposits, oil wells, timber tracts) over their extraction period. Because it closely matches the assets’ usage, depletion is often analogous to the Units-of-Production depreciation method. U.S. GAAP specifically addresses depletion within ASC 930 for extractive industries, but the basic principles also extend into standard property, plant, and equipment guidance (ASC 360) if the entity deals with natural resources.

#### Depletion Base

The depletion base typically includes:
• Acquisition costs of the natural resource.  
• Exploration and development costs directly attributable to the site (if capitalized).  
• Restoration costs or asset retirement obligations (AROs), where applicable.  
• Less any salvage value.  

#### Units-of-Production Depletion Formula

{{< katex >}}
\text{Depletion per unit} = \frac{\text{Total depletion base}}{\text{Estimated recoverable units}}
{{< /katex >}}

Multiply depletion per unit by the number of units extracted in the reporting period to determine the depletion expense for that period.

#### Example

• Company A acquires a mining site for \$500,000.  
• Estimated recoverable minerals = 250,000 units.  
• Residual land value (salvage) after mining = \$50,000.  
• Depletion base = \$500,000 – \$50,000 = \$450,000.  
• Depletion per unit = \$450,000 ÷ 250,000 units = \$1.80 per unit.  

If Company A extracts 30,000 units in Year 1, it records:
• Depletion Expense = 30,000 × \$1.80 = \$54,000.  

---

### Visualizing Depreciation and Depletion

Below is a Mermaid.js flowchart illustrating the typical decision process an entity may use when selecting depreciation or depletion methods.

```mermaid
flowchart LR
    A((Asset Acquisition)) --> B{Type of Asset}
    B --> C[Property, Plant, and Equipment]
    B --> D[Natural Resource]
    C --> E{Usage Pattern?}
    E --> F[Constant Usage<br>(Straight-Line)]
    E --> G[Accelerated Usage<br>(DDB or SYD)]
    D --> H[Depletion<br>(Units of Production)]
```

• Decision point 1: Determine if it is a typical fixed asset (PP&E) or a natural resource.  
• Decision point 2: If PP&E, assess usage: constant over time (SL) or accelerated in early years (DDB or SYD).  
• Decision point 3: For natural resources (e.g., oil, minerals), apply depletion via the Units-of-Production approach.  

---

### Handling Partial-Year Depreciation

Partial-year depreciation arises when assets are placed in service (or disposed of) at any point other than the start or end of the fiscal year. Common conventions include:

• Half-Year Convention: Treat every asset as if purchased exactly halfway through the year.  
• Mid-Month Convention: Used often for real estate, especially in U.S. tax contexts, where assets purchased in a given month are treated as acquired at the mid-point of that month.  
• Monthly/Quarterly Pro-Rata: Precisely apportion depreciation based on the fraction of the year the asset was in service.  

#### Example with Monthly Proration

• Purchase date: October 1 (start of Q4)  
• Annual depreciation (straight-line): \$12,000  
• Months in service during the year: 3 (October, November, December)  
• Depreciation for the initial year = (3/12) × \$12,000 = \$3,000  

---

### Best Practices and Implementation Notes

• Regularly re-evaluate the asset’s expected useful life for significant changes in usage patterns; adjust prospectively if it is a change in estimate.  
• For intangible assets (covered in Chapter 14), consider using the Straight-Line method if there is no predictable pattern of economic benefit.  
• Keep thorough documentation of assumption changes (e.g., salvage value, usage patterns).  
• Ensure you do not depreciate an asset below salvage value under any method.  
• Depletion should be periodically reassessed to reflect changes in recoverable reserves or resource estimates.  

---

### Common Pitfalls

1. Ignoring salvage value in accelerated methods, risking overstated depreciation.  
2. Failing to maintain consistent partial-year conventions from year to year.  
3. Applying accelerated methods without justification (e.g., an asset with constant usage).  
4. Overlooking the difference between the book basis for financial reporting versus tax basis depreciation. (While not always part of the exam, real-world practice sees differences due to IRS-mandated methods and MACRS tables in the U.S.)  

---

### IFRS Comparison

• IFRS (IAS 16) allows various depreciation methods (Straight-Line, Units-of-Production, or Accelerated) as long as it reflects the asset’s usage.  
• Revaluation model is available under IFRS, which can affect the carrying amount of assets but not directly the method of depreciation.  
• Salvage (residual) value and useful life must be reviewed at least annually under IFRS, prompting more frequent changes in estimates than may be observed under U.S. GAAP.  

---

### Practical Example: Comparing Depreciation Methods

Consider a machine costing \$100,000, with a \$10,000 salvage value and a 5-year useful life. Compare the depreciation in the first two years using three methods:

|                | Straight-Line       | DDB                | SYD                 |
|----------------|---------------------|--------------------|---------------------|
| Year 1         | (100k – 10k)/5 = 18k | 2/5 × 100k = 40k   | (5/15)*(100k–10k)=30k |
| NBV End of Y1  | 82k                | 60k                | 70k                 |
| Year 2 Dep.    | 18k                | 40% × 60k = 24k    | (4/15)*90k =24k     |
| NBV End of Y2  | 64k                | 36k                | 46k                 |

Note: The total depreciation over the asset’s entire life cannot exceed (C – S) = \$90,000. Methods differ by timing, not by total.

---

### References for Further Exploration

• FASB Accounting Standards Codification (ASC) 360: Property, Plant, and Equipment.  
• FASB ASC 930: Extractive Activities for industry-specific depletion.  
• IFRS IAS 16: Property, Plant, and Equipment for parallel IFRS guidance.  
• AICPA Practice Aid: “Accounting and Valuation Guide for Asset Acquisition” for advanced transaction examples.  

---

## Quiz on Depreciation Methods & Depletion

{{< quizdown >}}

### Which depreciation method allocates the cost evenly over the asset’s life?

- [x] Straight-Line
- [ ] Double-Declining Balance
- [ ] Sum-of-the-Years’-Digits
- [ ] Units-of-Production

> **Explanation:** The Straight-Line method applies a uniform depreciation expense each year, dividing (Cost – Salvage) by the estimated useful life.

### Which of the following statements is TRUE about the Double-Declining Balance method?

- [x] It uses a fixed rate (twice the SL rate) applied to the beginning book value each year.
- [ ] It does not accelerate depreciation compared to other methods.
- [ ] It calculates depreciation by summing the digits of the asset’s life.
- [ ] It is only used for intangible assets.

> **Explanation:** Double-Declining Balance (DDB) multiplies the constant 2/n rate by the book value at the beginning of each year, resulting in accelerated depreciation.

### The Sum-of-the-Years’-Digits (SYD) method is typically used when:

- [x] The asset’s benefits are realized more heavily in its early years.
- [ ] The salvage value is zero.
- [ ] The asset’s benefits remain constant throughout its life.
- [ ] The asset requires half-year convention.

> **Explanation:** SYD is an accelerated method that expenses more in the early years when an asset is typically more productive.

### Under U.S. GAAP, which financial reporting concept warrants using methods that reflect how the asset's economic benefits are consumed?

- [x] Matching Principle
- [ ] Monetary Principle
- [ ] Full Disclosure Principle
- [ ] Materiality Concept

> **Explanation:** The Matching Principle requires expenses to be recorded in the same period as the revenues they help generate, guiding the choice of an appropriate depreciation method.

### Which of the following is NOT a common partial-year depreciation convention?

- [x] Annual Max Convention
- [ ] Half-Year Convention
- [ ] Mid-Month Convention
- [ ] Monthly Pro-Rata Convention

> **Explanation:** “Annual Max Convention” is not a standard partial-year depreciation method.

### Under the Double-Declining Balance method, the book value of the asset:

- [x] Should never drop below its salvage value for financial reporting.
- [ ] Is calculated by multiplying cost by the sum of remaining digits.
- [ ] Is re-valued upward if the market value of the asset increases.
- [ ] Remains constant every year.

> **Explanation:** Accumulated depreciation is capped so that NBV generally should not go below salvage value in financial reporting under DDB.

### How do most companies handle assets that are purchased in the middle of the year?

- [x] They use partial-year depreciation, such as a monthly or half-year convention.
- [ ] They start depreciating only in the second year.
- [x] They prorate annual depreciation to reflect the months in service.
- [ ] They always use a full year’s depreciation in the year of purchase.

> **Explanation:** Entities often use partial-year calculations (e.g., monthly or half-year convention) to align depreciation with the asset’s time in service.

### The depletion base for natural resources typically excludes:

- [x] Non-capitalizable exploration costs that were expensed.
- [ ] Acquisition costs of the mine or source.
- [ ] Restoration obligations included in the asset retirement obligation (ARO).
- [ ] Development costs directly tied to extracting the resource.

> **Explanation:** Costs that are expensed as incurred (such as non-capitalizable exploration costs) are not included in the depletion base, while other costs like acquisition and restoration obligations are typically included.

### Which cost allocation method best applies to a coal mine with limited estimated reserves?

- [x] Units-of-Production (Depletion)
- [ ] Straight-Line
- [ ] Double-Declining Balance
- [ ] Sum-of-the-Years’-Digits

> **Explanation:** Natural resources are usually depleted using the Units-of-Production method, aligning expense with actual extraction.

### In IFRS, when must the useful life and residual value of assets be reviewed?

- [x] At least annually
- [ ] Once, when the asset is purchased
- [ ] Only when the asset is retired
- [ ] Never, unless there is a major revaluation event

> **Explanation:** IFRS requires reviewing the useful life and residual value at least annually to ensure accuracy in allocating costs over time.

{{< /quizdown >}}

---

## For Additional Practice and Deeper Preparation

**[FAR CPA Hardest Mock Exams: In-Depth & Clear Explanations](https://www.udemy.com/course/far-cpa-mock-exams/?referralCode=F88050F8D5C76764F6BD)**  

**Financial Accounting and Reporting (FAR) CPA Mocks:** 6 Full (1,500 Qs), Harder Than Real! In-Depth & Clear. Crush With Confidence! 

- Tackle full-length mock exams designed to mirror real FAR questions.  
- Refine your exam-day strategies with detailed, step-by-step solutions for every scenario.  
- Explore in-depth rationales that reinforce higher-level concepts, giving you an edge on test day.  
- Boost confidence and minimize anxiety by mastering every corner of the FAR blueprint.  
- Perfect for those seeking exceptionally hard mocks and real-world readiness.  

_Disclaimer: This course is not endorsed by or affiliated with the AICPA, NASBA, or any official CPA Examination authority. All content is for educational and preparatory purposes only._

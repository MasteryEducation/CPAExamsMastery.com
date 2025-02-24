---
title: "Formation & Contributions (§721) with Built-In Gain/Loss Property"
description: "Explore how §721 impacts nonrecognition of gain or loss upon formation of partnerships and LLCs, with a focus on carrying over basis, built-in gains/losses, disguised sale rules, and intangible contributions."
linkTitle: "11.1 Formation & Contributions (§721) with Built-In Gain/Loss Property"
date: 2025-02-07
type: docs
nav_weight: 4110
license: "© 2024 Tokenizer Inc. CC BY-NC-SA 4.0"
---

## 11.1 Formation & Contributions (§721) with Built-In Gain/Loss Property

When new or existing partners contribute property to a partnership or limited liability company (LLC) taxed as a partnership, Internal Revenue Code (IRC) §721 generally provides for the nonrecognition of gain or loss. This section spares the contributor from having to recognize immediate taxable gains or losses on property (including intangible property) exchanged solely for an interest in the partnership. While that rule sounds straightforward, details emerge regarding (1) built-in gains and losses embedded in contributed property, (2) the carryover of existing basis, and (3) the possible re-characterization under disguised sale rules. This chapter reconciles the fundamental principles of §721 with real-life complexities, highlighting key pitfalls to avoid in practice.

In this section, we will combine conceptual overviews with practical illustrations to enhance your understanding of the formation and contribution rules for partnerships and LLCs. Future sections, such as Chapter 11.2 (Partner’s Outside Basis vs. Partnership Inside Basis) and Chapter 11.3 (Special Allocations, Guaranteed Payments & §704(b)/(c) Rules), will define how these principles flow through and affect each partner’s distributive share and basis computations.

-------------------------------------------------------------------------------

### Overview of §721 Nonrecognition

Under §721(a), no gain or loss is recognized by a partner or partnership when property is contributed in exchange for a partnership interest—whether that interest is a capital interest, a profits interest, or both. For the purposes of partnership taxation, “property” includes cash, tangible property (e.g., real estate, equipment), and intangible property (e.g., patents, trademarks, goodwill). Services, however, are not treated as “property”; service providers who receive a partnership interest in exchange for services rendered may need to recognize ordinary income under §61 and potentially §83.

#### Key Insights

• The intent behind §721 is to facilitate business formation without creating immediate tax friction.  
• The exchange is not fully tax-free in an absolute sense; it is merely the deferral of any built-in gain or loss until eventual disposition by the partnership or the partner.  
• Ongoing rules in other sections—such as §§704(b), 704(c), 737, and 707—help ensure that deferred gain or loss is eventually taxed, and that each partner bears their fair share of economic gain or loss.

-------------------------------------------------------------------------------

### Carryover Basis Rules

While §721 provides for nonrecognition, it does not necessarily eliminate built-in gains or losses; these remain “locked in” to the contributed property. Both the contributing partner’s outside basis and the partnership’s inside basis in the property are governed by carryover rules found in §§723 and 722.

1. **Partnership’s Inside Basis (§723).** Upon contribution, the partnership’s basis in the property typically equals the contributing partner’s adjusted basis immediately before contribution.  
2. **Partner’s Outside Basis (§722).** The contributing partner’s outside basis (their tax basis in the partnership interest) ordinarily equals the adjusted basis of the property contributed, plus any cash contributed, plus any gain recognized (if relevant exceptions require recognition).

Below is a simple diagram illustrating these basis flows:

```mermaid
flowchart LR
    A[Partner A] -- Contributes Property (Adjusted Basis) --> B[(Partnership)]
    B -- Receives Carryover Basis --> D[Inside Basis in Property]
    A -- Receives --> C[Partnership Interest]
    C -- Has Outside Basis = Adjusted Basis of Contributed Property
```

In the above diagram, Partner A transfers property to the partnership. The partnership obtains a carryover inside basis in that property (D), while Partner A receives an interest in the partnership (C). Partner A’s outside basis equals the adjusted basis of the contributed property.

#### Special Considerations

• **Liabilities**: When a partner contributes property subject to a liability (e.g., a mortgage), the partner’s share of that liability becomes part of their outside basis. However, to the extent the liability is “shifted” to other partners, the contributing partner might face a reduction in basis and potential gain recognition.  
• **Multiple Contributing Partners**: Each asset’s basis is tracked individually in the partnership for future depreciation, amortization, or gain/loss on sale. If multiple assets with different built-in gains or losses are contributed, the partnership must maintain accurate records for each asset.  
• **Adjustments upon Sale**: If the partnership later sells the contributed asset, the built-in gain or loss is typically recognized at that time and, under §704(c) and related regulations, allocated to the contributing partner to prevent shifting of tax consequences.

-------------------------------------------------------------------------------

### Built-In Gain and Loss Property

A “built-in” gain or loss is the difference between the fair market value (FMV) of property and its adjusted tax basis. By contributing property with a built-in gain or loss, the contributing partner effectively defers recognition until the property’s disposition or until another triggering event.

#### Built-In Gains

• **Example**: Partner A contributes land with an FMV of $200,000 and a basis of $100,000; there is $100,000 of built-in gain. Under §721, no gain is recognized on contribution. If the partnership later sells the land for $210,000, the built-in gain of $100,000 (plus any additional appreciation) is recognized and specially allocated back to Partner A under §704(c).  
• **Accelerated Recognition**: Certain transactions (e.g., distributions to other partners or subsequent property sales) may trigger recognition of the built-in gain earlier than expected under regulations aiming to preclude shifting built-in gain to other partners.

#### Built-In Losses

• **Example**: Partner B contributes real estate with an FMV of $80,000 and an adjusted basis of $120,000; there is a $40,000 built-in loss. The partnership’s inside basis remains $120,000, but for tax accounting and future allocations, that $40,000 built-in loss is associated with Partner B. Should the partnership sell the property at its contributed value of $80,000, that $40,000 loss is allocated to Partner B.  
• **Loss Limitation**: If the partnership is unlikely ever to sell the property for an amount lower than $120,000, Partner B’s built-in loss essentially remains unrecognized (and effectively “stranded”) within the partnership. Additionally, Congress has enacted provisions to limit the recognition of a built-in loss if the property has significantly declined in value before contribution, restricting potential tax benefits.

-------------------------------------------------------------------------------

### Tangible vs. Intangible Property Contributions

#### Tangible Property
Tangible assets (e.g., land, buildings, equipment) follow straightforward basis-carryover principles. The partnership’s inside basis equals the basis of the contributing partner, adjusted for liabilities. The built-in gain or loss is recognized if and when the partnership disposes of the property.

#### Intangible Property
Patents, copyrights, and other intangibles pose special tax complexities:

1. **Amortization**: Certain intangibles, such as acquired patents or goodwill, may be amortizable over statutory periods. If contributed, the partnership inherits the contributor’s amortization schedule and basis.  
2. **§197 Intangibles**: Goodwill, going-concern value, and other intangible assets defined under §197 are subject to a 15-year amortization. If an intangible has a built-in gain or loss, the partnership still defers recognition under §721, but basis is carried over according to the partner’s adjusted basis rules.  
3. **Royalty Streams**: If a partner contributes intangible property rights subject to existing royalty agreements, complex allocation rules can apply if proceeds from the licenses are considered partnership income. Partners must be especially careful to identify whether a portion of the arrangement could be recharacterized as a disguised sale or payment for services.

-------------------------------------------------------------------------------

### Potential Pitfalls: Disguised Sales

Provisions under §707(a)(2)(B) and related Treasury Regulations address “disguised sales,” a common pitfall for unsuspecting partners. A disguised sale occurs when a partner receives (or is deemed to receive) a distribution of cash or other property in connection with, or shortly after, contributing property to a partnership—effectively disguising what might otherwise be treated as a sale.

#### Hallmarks of a Disguised Sale

• **Timing of Distributions**: If the partnership issues distributions to a partner near (within two years) the date of contribution, the transaction is presumed to be a disguised sale, unless facts and circumstances demonstrate otherwise.  
• **Shifting Economic Risk**: A disguised sale may be identified if the contributing partner no longer retains the risks and rewards of ownership of the property.  
• **Contribution Followed by “Immediate” Distribution**: For example, Partner A contributes appreciated real estate worth $2 million and soon thereafter receives $1.8 million in cash from the partnership. Absent mitigating factors, the IRS may treat this as a taxable sale of the property rather than a mere nonrecognition transaction.

#### Consequences of Disguised Sales

If a contribution and associated distribution is recharacterized as a disguised sale, the partner may be subject to immediate gain recognition on the difference between the FMV of the property and its adjusted tax basis (minus recognized liabilities). Additionally, the partnership’s basis in the property is stepped up to the purchase price, and the partner’s outside basis is adjusted to reflect a sale transaction.

-------------------------------------------------------------------------------

### Interplay with §704(c) Allocations

Section 704(c) ensures that tax items related to built-in gain or loss are allocated to the contributing partner. This prevents the shifting of pre-contribution economic consequences to other partners. Although the general rule of nonrecognition under §721 applies at formation, the built-in gain or loss is preserved and tracked via §704(c) mechanisms. Special allocations—often recognized as the traditional method, curative allocations, or remedial allocations—are designed to closely reflect the underlying economics.

-------------------------------------------------------------------------------

### Illustrative Example

Let’s illustrate a comprehensive scenario showing many of the issues discussed:

1. **Entity Formation**: Alpha LLC, taxed as a partnership, is formed by Partner X and Partner Y.  
2. **Contributions**:  
   - Partner X contributes a parcel of land with an FMV of $400,000 and an adjusted basis of $200,000. The land is subject to a $50,000 mortgage.  
   - Partner Y contributes $350,000 of cash.  
3. **Potential Built-In Gain**: Partner X effectively defers a $200,000 built-in gain ($400,000 FMV – $200,000 basis).  
4. **Adjustment for Liabilities**: Because the land is subject to a $50,000 liability, the partnership’s inside basis is $200,000 (carryover) plus the assumption of the $50,000 liability. However, the liability is allocated among partners according to the partnership agreement and the rules in §§752 and 704.  
5. **Partner X’s Outside Basis**:  
   - Initial outside basis = $200,000 (land basis) – $50,000 (liability assumed by the partnership and possibly partly by Y, pending a deeper liability allocation analysis) + Partner X’s share of partnership liabilities.  
6. **No Immediate Gain Recognition**: Because this arrangement is purely a contribution for an interest in Alpha LLC, there is no immediate gain recognized, provided that no disguised sale factors are triggered.  
7. **Subsequent Disguised Sale Risk**: Suppose that three months later, the partnership distributes $300,000 to X. The IRS may examine if this is a disguised sale of the land. If concluded to be a disguised sale, X would have to recognize some or all of the built-in gain. Conversely, if X can demonstrate legitimate business purposes (e.g., an operating agreement requiring distributions to each partner in proportion to capital contributions, including a distribution to Y that is proportionate), then this might not be characterized as a disguised sale.  
8. **Later Disposition**: When the partnership eventually sells the land, the $200,000 built-in gain (potentially more if property value appreciates) would be allocated to X under §704(c). If the land sells for $410,000, an additional $10,000 is allocated among the partners under the partnership’s allocation method in the partnership agreement.

This example shows how the puzzle pieces—§721 nonrecognition, debt allocation, built-in gains, potential disguised sales, and later allocations—fit together in practice.

-------------------------------------------------------------------------------

### Common Pitfalls and Best Practices

1. **Not Evaluating Timing of Distributions**: Partners often forget that distributions near the time of property contributions may trigger §707 disguised sale rules. Best practice is to delay large distributions tied to a partner’s contribution, or ensure that distributions are made pro rata and reflect normal return of capital or operating cash flow.  
2. **Failure to Track Built-In Gains and Losses**: Partnerships must maintain detailed schedules of each contributed asset’s inside basis and FMV at contribution. This is essential for §704(c) allocations and for calculating partner capital accounts over time.  
3. **Inadequate Operating Agreements**: Lack of clarity about liability allocations, distributions, and repurchase rights can produce unintended tax consequences. Thoughtful drafting can prevent a potential disguised sale.  
4. **Service Contributions**: Mistaking services for property is a major misstep. If a partner provides services, ordinary income generally must be recognized if the partner receives a capital interest. For a profits interest, special rules apply (Revenue Procedure 93-27, as clarified by Revenue Procedure 2001-43).  
5. **Intangible Valuation**: Over- or under-valuing intangible property can trigger future disputes with the IRS. Partnerships need thorough valuation opinions to substantiate FMV and to properly monitor any built-in gain or loss.  
6. **Ignoring State-Level Variations**: Many states follow federal partnership rules, but not all. Some states may require separate valuations or recognition triggers. Confirm alignment of federal, state, and local requirements during formation.  

-------------------------------------------------------------------------------

### Practical Tips and Strategies

• **Detailed Valuations**: Engage reputable valuation specialists, especially for significant intangible property, to support your claimed FMV.  
• **Thorough Legal Documentation**: Partner agreements should spell out the capital structure, contributions, distribution policies, and intangible asset ownership.  
• **Proactive Disclosure**: If your transaction is a close call under disguised sale rules, consider seeking professional advice and, in certain cases, a Private Letter Ruling (PLR) for clarity.  
• **Cross-Reference to §704(c)**: Since built-in gain or loss will be subject to special allocations upon a future disposition, carefully coordinate capital accounts. (See Chapter 11.3 for in-depth coverage.)  
• **Layer In §752 Liabilities**: The rules for allocating partnership liabilities can drastically affect the partner’s outside basis (and potential gain recognition). Evaluate the risk of excessive liability shifting.  
• **Monitor Holding Periods**: For capital gain classification, watch for the partnership’s holding period integration. The partner’s holding period for their contributed property usually tacks on to the partnership’s holding period in that property (though complexities exist for split holding periods if property was partly capital and partly ordinary).

-------------------------------------------------------------------------------

### Diagrams and Tables

Below is a high-level infographic summarizing how property contributions integrate into a partnership’s tax structure:

```mermaid
flowchart TB
    P1((Partner 1)) --> |Contribute Assets| PR[(Partnership)]
    P2((Partner 2)) --> |Contribute Assets| PR
    P3((Partner 3)) --> |Contribute Assets| PR
    PR -- "Inside Basis = Sum of Adjusted Bases" --> PR
    PR --> |Distributions/Allocations| P1
    PR --> |Distributions/Allocations| P2
    PR --> |Distributions/Allocations| P3
    note right of PR: Check for Built-In Gains & Disguised Sales
```

#### Table 1: Overview of Common IRC Sections Affecting §721

| IRC Provision  | Key Topic                        | Relevance                                                                 |
|----------------|----------------------------------|---------------------------------------------------------------------------|
| §721           | Nonrecognition of Gain/Loss      | Governs primary rule for tax-free contributions to a partnership          |
| §722           | Partner’s Outside Basis          | Determines partner’s basis in the partnership interest post-contribution  |
| §723           | Partnership’s Inside Basis       | Partnership’s basis in contributed assets follows the contributing partner’s basis |
| §704(c)        | Built-In Gain/Loss Allocations   | Ensures that pre-contribution gains/losses are allocated to the contributor |
| §707           | Disguised Sale & Related Rules   | Distributions near contributions may be recharacterized as a sale         |
| §197           | Amortizable Intangibles          | Covers partnership’s amortization of contributed goodwill or like intangibles |
| §752           | Liability Allocation             | Affects computation of partner’s outside basis                            |

-------------------------------------------------------------------------------

### References for Further Exploration

• IRS Publication 541, “Partnerships”—Provides an overview of partnership formation, distributions, taxation, and compliance.  
• Treasury Regulations §§1.707-3 through 1.707-9—Offer detailed guidance on disguised sales of property to or by a partnership.  
• “Partnership Taxation” by William S. McKee, William F. Nelson, and Robert L. Whitmire—A comprehensive treatise on the complexities of Subchapter K, important for advanced research.  
• Chapter 11.2 (in this text)—Delves deeper into Partner’s Outside Basis vs. Partnership Inside Basis.  
• Chapter 11.3 (in this text)—Explores Special Allocations, Guaranteed Payments & §704(b)/(c) Rules.

-------------------------------------------------------------------------------

## Quiz on §721 Formation, Built-In Gains/Losses & Disguised Sales

{{< quizdown >}}

### Which statement best describes the nonrecognition rule under IRC §721?
- [x] It generally allows partners to defer gain or loss on property contributed to a partnership in exchange for an interest.  
- [ ] It provides for immediate recognition of all built-in gains on contributed property.  
- [ ] It requires partners to amortize intangible property over five years.  
- [ ] It never applies if a partner contributes both cash and property.  

> **Explanation:** IRC §721 permits the nonrecognition of gain or loss when property is contributed to a partnership solely in exchange for a partnership interest. Built-in gains and losses remain deferred until later disposition.

### What happens to a contributing partner’s outside basis after transferring property to a partnership?
- [x] It generally equals the partner’s adjusted basis in the contributed property plus any cash contributed (and adjusted for liabilities).  
- [ ] It is always set at the property’s fair market value on the day of contribution.  
- [ ] It is determined by the partnership’s total assets.  
- [ ] It remains permanently unchanged.  

> **Explanation:** Under §722, a partner’s outside basis is generally the adjusted basis of contributed assets + any additional cash, taking into account relevant liability allocations.

### How are built-in gains or losses treated under §721 at the time of contribution?
- [x] The gain or loss is deferred and not recognized immediately.  
- [ ] The gain or loss must be reported as ordinary income.  
- [ ] The IRS requires immediate self-assessment taxes on built-in gains only.  
- [ ] The gain or loss is recognized only if it exceeds $100,000 per transaction.  

> **Explanation:** The essence of §721 is that any built-in gain or loss remains deferred until a triggering event (e.g., sale, distribution) occurs in the future.

### Which provision is primarily concerned with disguised sale rules in a partnership context?
- [x] IRC §707(a)(2)(B).  
- [ ] IRC §1244.  
- [ ] IRC §351.  
- [ ] IRC §179.  

> **Explanation:** IRC §707(a)(2)(B) and associated regulations address when a contribution by a partner and a related distribution by the partnership should be recharacterized as a disguised sale.

### If a partner contributes intangible property with a built-in loss, how is this typically handled for tax purposes?
- [x] The partnership takes a carryover basis, and the built-in loss remains deferred until eventual disposition.  
- [ ] The partner must immediately recognize the loss.  
- [x] The partner’s built-in loss is tracked under §704(c) for potential special allocations upon disposition.  
- [ ] The partnership’s basis is adjusted to fair market value at contribution.  

> **Explanation:** Under §723, the partnership steps into the contributor’s basis, which includes a built-in loss. Future disposition triggers recognition allocated back to the contributor under §704(c).

### Which factor might help the IRS identify a disguised sale in a partnership formation?
- [x] Significant cash distribution to the contributing partner within two years of contribution with no other business justification.  
- [ ] A formal Section 721 statement filed with the partnership return.  
- [ ] The presence of intangible property valued at under $1,000.  
- [ ] Multiple partners entering the partnership at the same time.  

> **Explanation:** A key hallmark is a partner who contributes property and receives a large distribution shortly thereafter, which may signal a disguised sale unless there are legitimate facts otherwise.

### What is the principal reason for special allocations under §704(c) concerning contributed property?
- [x] To ensure the contributing partner bears or enjoys the tax consequences of any pre-contribution built-in gain or loss.  
- [ ] To guarantee the partnership recognizes ordinary income at the time of contribution.  
- [x] To allocate intangible property to non-contributing partners.  
- [ ] None of the above.  

> **Explanation:** Section 704(c) allocations fix the economic distortion that would occur if built-in gain or loss from contributed property were shared by all partners rather than allocated to the contributor.

### How do partnership liabilities affect a contributing partner’s outside basis?
- [x] The partner’s outside basis may increase or decrease based on how much of the partnership liability is allocated to that partner.  
- [ ] Partnership liabilities do not affect a partner’s outside basis under federal law.  
- [ ] The partner’s outside basis is always reduced by the full amount of the liability.  
- [ ] The partner’s outside basis is unchanged by the presence of liabilities.  

> **Explanation:** Under §752, premiums of liability allocation can increase a partner’s basis, while a shift of debt to other partners can reduce the contributing partner’s basis, potentially creating gain recognition.

### If a partner contributes property subject to a liability exceeding the partner’s basis in the property, which outcome is most likely?
- [x] The partner may have to recognize gain to the extent the liability transferred exceeds their adjusted tax basis.  
- [ ] The partner earns an automatic deduction equal to the excess liability.  
- [ ] The liability is ignored for tax purposes.  
- [ ] The partnership must capitalize the liability as intangible property.  

> **Explanation:** When total liabilities assumed by the partnership exceed the partner’s basis in contributed property, it can trigger gain recognition under partnership contribution rules.

### True or False: Section 721 nonrecognition applies even if the partner contributes both property and services to the partnership.
- [x] True  
- [ ] False  

> **Explanation:** A partner contributing services (for a capital interest) generally recognizes income for the service component. However, if the partner also contributes property, that part of the transaction can still qualify for nonrecognition under §721. The service portion is subject to its own rules.

{{< /quizdown >}}

-------------------------------------------------------------------------------

## For Additional Practice and Deeper Preparation

**[TCP CPA Hardest Mock Exams: In-Depth & Clear Explanations](https://www.udemy.com/course/tcp-cpa-mock-exams/?referralCode=675149871D0E79B1699C)**  

**Tax Compliance & Planning (TCP) CPA Mocks:** 6 Full (1,500 Qs), Harder Than Real! In-Depth & Clear. Crush With Confidence!

- Tackle full-length mock exams designed to mirror real TCP questions.  
- Refine your exam-day strategies with detailed, step-by-step solutions for every scenario.  
- Explore in-depth rationales that reinforce higher-level concepts, giving you an edge on test day.  
- Boost confidence and minimize anxiety by mastering every corner of the TCP blueprint.  
- Perfect for those seeking exceptionally hard mocks and real-world readiness.

_Disclaimer: This course is not endorsed by or affiliated with the AICPA, NASBA, or any official CPA Examination authority. All content is for educational and preparatory purposes only._

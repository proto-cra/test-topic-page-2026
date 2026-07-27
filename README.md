# Test topic page

*description of the project*

**Timeframe** 2026-07-13 - 2026-10-19

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://proto-cra.github.io/test-topic-page-2026](https://proto-cra.github.io/test-topic-page-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-07-27

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(Sign in to your CRA account)
    node4(Update your information with the CRA)
    node5(Update your personal information with the CRA)
    node6(Update your personal information with the CRA – Change your address)
    node7(Support from the CRA during difficult situations)
    node8(Getting your tax benefits and credits when in an abusive situation)
    node9(New page)
    node10(People experiencing housing insecurity and the CRA)
    node11(Skip the Line – Get faster help from the CRA)
    node12(Benefits)
    node13(Benefits payment dates)
    node14(Benefits Finder)
    node15(Taxes)
    node16(Income tax)
    node17(Personal income tax)
    node18(Claiming deductions, credits, and expenses)
    node19(All deductions, credits and expenses - Personal income tax)
    node20(Canada workers benefit #40;CWB#41; – Personal income tax)
    node21(Canada training credit – Personal income tax)
    node22(Home accessibility expenses – Personal income tax)
    node23(Canada caregiver credit)
    node24(Persons with disabilities, their caregivers, and the CRA)
    node25(Taxes when you retire or turn 65 years old)
    node26(Who should file a tax return)
    node27(Individuals – Leaving or entering Canada and non-residents)
    node28(Newcomers to Canada and the CRA)
    node29(Students)
    node30(How to file a tax return – Personal income tax)
    node31(Learn about your taxes)
    node32(Tax credits and benefits for individuals)
    node33(Overview of child and family benefits)
    node34(Child and family benefits calculator)
    node35(Child disability benefit #40;CDB#41;)
    node36(Children's special allowances #40;CSA#41;)
    node37(GST/HST credit - No longer available)
    node38(One-time GST/HST credit top-up payment #40;issued June 5, 2026#41;)
    node39(Canada child benefit #40;CCB#41;)
    node40(Canada Groceries and Essentials Benefit #40;CGEB#41;)
    node41(Disability tax credit #40;DTC#41;)
    node42(Closed - Canada Carbon Rebate #40;CCR#41; for individuals)
    node43(GST/HST break - Closed)
    node44(Provincial and territorial programs)
    node45(Province of Alberta)
    node46(Province of British Columbia)
    node47(Province of New Brunswick)
    node48(Province of Newfoundland and Labrador)
    node49(Northwest Territories)
    node50(Province of Nova Scotia)
    node51(Nunavut)
    node52(Province of Ontario)
    node53(Province of Prince Edward Island)
    node54(Province of Quebec)
    node55(Province of Saskatchewan)
    node56(Yukon)
    node57(Province of Banana)
    node1 --x node2
    node2 --> node3
    node2 --> node4
    node4 --> node5
    node5 --> node6
    node2 --> node7
    node7 --> node8
    node8 --> node9
    node2 --x node10
    node2 --> node11
    node1 --> node12
    node12 --> node13
    node12 --x node14
    node1 --> node15
    node15 --> node16
    node16 --> node17
    node17 --> node18
    node18 --> node19
    node19 --> node20
    node19 --> node21
    node19 --> node22
    node18 --x node23
    node17 --> node24
    node17 --> node25
    node17 --> node26
    node26 --x node27
    node27 --> node28
    node17 --> node29
    node17 --> node30
    node17 --> node31
    node15 --> node32
    node32 --> node33
    node33 --> node34
    node33 --> node35
    node33 --> node36
    node32 --> node37
    node37 --> node38
    node32 --> node39
    node32 --> node40
    node32 --> node41
    node32 --> node42
    node32 --> node43
    node32 --> node44
    node44 --> node45
    node44 --> node46
    node44 --> node47
    node44 --> node48
    node44 --> node49
    node44 --> node50
    node44 --> node51
    node44 --> node52
    node44 --> node53
    node44 --> node54
    node44 --> node55
    node44 --> node56
    node44 --> node57

    classDef inscope stroke:#7636ab,stroke-width:3px
    class node3,node6,node8,node9,node10,node11,node13,node14,node18,node20,node21,node22,node23,node24,node25,node28,node29,node30,node31,node34,node35,node36,node38,node39,node40,node41,node42,node43,node44,node45,node46,node47,node48,node49,node50,node51,node52,node53,node54,node55,node56,node57 inscope
    classDef isnew fill:#00706f,color:#fff
    class node9,node57 isnew
    classDef ismoved fill:#eab308,color:#000
    class node44 ismoved
```

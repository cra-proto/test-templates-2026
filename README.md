# Various templates

*description of the project*

**Timeframe** 2026-07-14 - 2026-10-20

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/test-templates-2026](https://cra-test-arc.canada.ca/test-templates-2026)

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

**Updated:**  2026-07-28

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(Every dollar counts)
    node4(Contact the Canada Revenue Agency #40;CRA#41;)
    node5(Scams and fraud - CRA)
    node6(CRA Multimedia library banana)
    node7(Business video gallery)
    node8(Individuals video gallery)
    node9(Charities media gallery)
    node10(Podcasts)
    node11(CRA Newsroom)
    node12(Enforcement notifications: compliance actionsababababa)
    node13(Drone flight operations company grounded following COVID-19 subsidy fraud and tax evasion)
    node14(New page)
    node15(Tax tips 2026)
    node16(Avoid tax season surprises by keeping your CRA account up to date!)
    node17(New page)
    node18(Test)
    node19(Forms and publications - CRA)
    node20(All personal income tax packages)
    node21(ARCHIVED - Get a T1 income tax package for 2023)
    node22(New page)
    node23(Get a T1 income tax package)
    node24(Federal Income Tax and Benefit Information for 2025)
    node25(Alberta - 2025 Income tax package)
    node26(5009-C AB428 - Alberta Tax and Credits)
    node27(New page)
    node28(TD1 Personal Tax Credits Returns)
    node29(TD1 forms for 2026 for pay received on January 1, 2026 or later)
    node30(TD1 2026 Personal Tax Credits Return)
    node31(New page)
    node32(Taxes)
    node33(Payroll)
    node34(Tax credits and benefits for individuals)
    node35(Canada child benefit #40;CCB#41;)
    node36(Contact us)
    node37(Who can apply)
    node38(Income tax)
    node39(Sole proprietorships and partnerships)
    node40(T5013 Partnership Information Return filing requirements)
    node41(Electronic filing for T5013 Partnership Information Return)
    node42(Topics – Partnerships)
    node43(Doing taxes for someone who died)
    node44(Brochure: Doing taxes for someone who died)
    node45(Personal income tax)
    node46(What you need to send us on behalf of your client to support a claim selected for review)
    node47(Who should file a tax return)
    node1 --x node2
    node2 --x node3
    node3 --> node4
    node3 --> node5
    node5 --x node6
    node6 --> node7
    node6 --> node8
    node6 --> node9
    node6 --> node10
    node3 --> node11
    node11 --> node12
    node12 --> node13
    node13 --> node14
    node11 --x node15
    node15 --x node16
    node16 --> node17
    node16 --> node18
    node2 --> node19
    node19 --> node20
    node20 --> node21
    node21 --> node22
    node20 --> node23
    node23 --x node24
    node23 --> node25
    node25 --> node26
    node26 --> node27
    node19 --x node28
    node28 --> node29
    node29 --> node30
    node30 --> node31
    node1 --> node32
    node32 --> node33
    node32 --> node34
    node34 --> node35
    node35 --> node36
    node35 --> node37
    node32 --> node38
    node38 --x node39
    node39 --> node40
    node40 --> node41
    node39 --x node42
    node38 --> node43
    node43 --> node44
    node38 --> node45
    node45 --x node46
    node45 --> node47

    classDef inscope stroke:#7636ab,stroke-width:3px
    class node3,node4,node5,node6,node7,node8,node9,node10,node13,node14,node16,node17,node18,node21,node22,node24,node26,node27,node30,node31,node33,node35,node36,node37,node41,node42,node44,node46,node47 inscope
    classDef isnew fill:#00706f,color:#fff
    class node14,node17,node18,node22,node27,node31 isnew
    classDef ismoved fill:#eab308,color:#000
    class node4,node5,node6,node11 ismoved
```

# test-templates

*description of the project*

**Timeframe** 2026-08-05 - 2026-11-11

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

**Updated:**  2026-08-19

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(CRA Forms and publications)
    node4(All personal income tax packages)
    node5(Get a T1 income tax package)
    node6(Federal Income Tax and Benefit Information for 2025)
    node7(TD1 Personal Tax Credits Returns)
    node8(TD1 forms for 2026 for pay received on January 1, 2026 or later)
    node9(TD1 2026 Personal Tax Credits Return)
    node10(Every dollar counts)
    node11(Contact the Canada Revenue Agency #40;CRA#41;)
    node12(Scams and fraud - CRA)
    node13(CRA Multimedia library)
    node14(Individuals video gallery)
    node15(Podcasts)
    node16(Payments – CRA)
    node17(Prescribed interest rates)
    node18(Interest rates for the third calendar quarter)
    node19(Old broken link)
    node20(Page supprimees)
    node21(New page)
    node22(Page supprimee)
    node23(Taxes)
    node24(Tax credits and benefits for individuals)
    node25(Canada child benefit #40;CCB#41;)
    node26(Contact us)
    node27(Who can apply)
    node28(Income tax)
    node29(Sole proprietorships and partnerships)
    node30(Topics – Partnerships)
    node31(Doing taxes for someone who died)
    node32(Brochure: Doing taxes for someone who died)
    node33(Personal income tax)
    node34(What you need to send us on behalf of your client to support a claim selected for review)
    node35(Who should file a tax return)
    node36(Payroll)
    node1 --x node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    node5 --x node6
    node3 --x node7
    node7 --> node8
    node8 --> node9
    node2 --x node10
    node2 --> node11
    node11 --> node12
    node2 --x node13
    node13 --> node14
    node13 --> node15
    node2 --> node16
    node16 --> node17
    node17 --> node18
    node2 --> node19
    node2 --> node20
    node2 --> node21
    node2 --> node22
    node1 --> node23
    node23 --> node24
    node24 --> node25
    node25 --> node26
    node25 --> node27
    node23 --> node28
    node28 --x node29
    node29 --x node30
    node28 --> node31
    node31 --> node32
    node28 --> node33
    node33 --x node34
    node33 --> node35
    node23 --> node36

    classDef inscope stroke:#7636ab,stroke-width:3px
    class node6,node9,node10,node11,node12,node14,node15,node16,node17,node18,node19,node20,node21,node22,node25,node26,node27,node28,node30,node32,node34,node35,node36 inscope
    classDef isnew fill:#00706f,color:#fff
    class node19,node20,node21,node22 isnew
    classDef ismoved fill:#eab308,color:#000
    class node12 ismoved
```

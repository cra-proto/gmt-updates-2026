# GMT updates

*description of the project*

**Timeframe** 2026-06-11 - 2026-09-17

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/gmt-updates-2026](https://cra-test-arc.canada.ca/gmt-updates-2026)

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

**Updated:**  2026-06-25

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Excise and specialty taxes)
    node4(Global minimum tax)
    node5(About the tax)
    node6(Contact us)
    node7(Global minimum tax: Questions and Answers)
    node8(File your returns)
    node9(Payments)
    node10(Registering for an account)
    node11(Who must file a return or notification)
    node12(Request a technical interpretation)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    node4 --> node6
    node6 --> node7
    node4 --> node8
    node4 --> node9
    node4 --> node10
    node4 --> node11
    node4 --x node12
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/services/taxes.html" _blank
    click node3 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies.html" _blank
    click node4 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies/global-minimum-tax.html" _blank
    click node5 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies/global-minimum-tax/about.html" _blank
    click node6 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies/global-minimum-tax/contact.html" _blank
    click node7 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies/global-minimum-tax/contact/global-minimum-tax-faq.html" _blank
    click node8 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies/global-minimum-tax/file-your-returns.html" _blank
    click node9 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies/global-minimum-tax/pay-the-tax.html" _blank
    click node10 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies/global-minimum-tax/register-account.html" _blank
    click node11 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies/global-minimum-tax/who-must-file.html" _blank
    click node12 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies/global-minimum-tax/request-technical-interpretation.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4,node5,node6,node7,node8,node9,node10,node11,node12 inscope
```

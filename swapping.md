---
tags:
  - data
  - code
  - data-science
  - differential-privacy
---

Swapping is a technique used to ensure [[differential-privacy]] is maintained. According to `(Ted)+` in [[demystifying-the-us-census-bureau-reconstruction-attack]], the process is completed in the following way:
	1. Households are selected at random from small geographic units. Those households become individual components in a the geographic sample space. Information about the people living in those households can now also be revealed if anonymization isn't upheld.
	2. Next the data about those household members are *swapped* with other households, either within or from outside the original household selections. Wild!
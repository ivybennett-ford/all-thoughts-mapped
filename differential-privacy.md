# Differential privacy
---
```ad-note
title: To keep in mind
Differential privacy is a relational structure used to distinguish secure and unsecure data as returned by a machine learning model
```

Differential privacy is a reinforceable dataset quality. It describes a choice the investigator makes about the data they work with, and the outcome of that choice. 

A differentially private framework is successful if the substitution of one pool subject for another does not reveal unique identifiers about the individuals in question. Those unique identifiers would reveal personal, memorable information about the dataset members. 

To have [[knowledge]] of their identities would be a breach of ethics -- ultimately, the results of the investigative [[model]] would have to be negated, or at the very least, could not possibly be trusted. 

Because we live in a data-driven world, where information becomes knowledge, revealed characteristics would irrevocably impact the lives of the dataset members, and the lifecycle of whatever data pipeline the investigator was trying to build in the first place. The investigator must therefore be aware of what could go wrong. The constructed model should be aware of what kinds of information could nullify

### Compromised privacy
In the case of [Sweeney's [[k-anonimity]]](https://desfontain.es/privacy/k-anonymity.html), privacy was compromised by leaving 'some demographic information' in the data-set of [[user]] information. However, it is not clear which aspects of demographic data are left-over? According to above source, the ZIP code, date of birth and sex were exposed in the anonymized target dataset.

### Open data privacy

Is the data handed to us [[open-data|open-data]] or [[closed-data]]?


### Definitive sources
---
[Open Data Privacy Handbook](https://dash.harvard.edu/bitstream/handle/1/30340010/OpenDataPrivacy.pdf?sequence=5&isAllowed=y)

[The Definition of Differential Privacy by Cynthia Dwork](https://www.youtube.com/watch?v=lg-VhHlztqo&t=612s)

[Differential Privacy + Federated Learning Explained by Jordan Harrod](https://www.youtube.com/watch?v=MOcTGM_UteM)

[Protecting Privacy with MATH](https://www.youtube.com/watch?v=pT19VwBAqKA)

### Differential Privacy a la Dwork, McSherry, Nissim, Smith
---
'$M$ gives $\in$-differential privacy if for all pairs of data sets $x,y$ differing in the data of one person and all events, $S$'

>$Pr[M(x) \in S] \le e^{\in} Pr[M(y) \in S$

### Awareness and consequence
---

The investigator must decide what qualities should be kept hidden, what unique identifiers would categorically alter the results of the [[model]]. Then they must decide if the suppression of unique identifiers serves the integrity of the system, or the benefit of a chosen few.

Data theft has contributed to the foundations of modern data science for as long as human history has been recorded. 

Although as investigators we are interested in the fair and ethical thing to do, it is unreasonable to expect a categorically problematic foundation to withstand scrutiny.

[[spatial-knowledge]]
[[cosmopolitanism-and-the-geographies-of-freedom]]
[[space]]
[[place]]
[[swapping]]




### Key questions
---
- What do we reveal by removing layers of privacy, if what we want to know about is inherently not private?
	- Are we indeed trying to deobfuscate 'private' information? 
	- Is this unethical?
- What information do we currently possess (i.e. use) that is prevalent to individual identities?
	- What data do we currently use?

### Reverse-engineering privacy
![[attempt-to-reconstruct-confidential-data-using-public-data]]


### BlueConduit Project Spec
- ***Brief***: attempt to reverse engineer privacy from a given client's data for a specific service area, using Dwork et al's algorithm above. 
	- Optimizing for privacy works very well in cases like the medical field, where anonymized or patient-released data is built into the system already
	- This happens by injecting noise into the model and optimizing for the feature of interest -- this optimization depends on the regime, the context
	- This is not the case for cities -- privacy is expected as an ethical courtesy, but is not built into any existing systems of government
		- Should BC try to preserve the status quo, or use [[data]] to restore or bolster privacy
- ***Deliverables*** 
	- A report on privacy at BlueConduit
- ***Future work***
	- If privacy is determined to be an issue, could forsee developing a module in evaluation.py
- Super private 

- [x] ### Draft email to SB re: their work
Dear Sarah,
I hope this finds you well. My name is Ivy, I work with Sydney Treu. They kindly connected me to you! Your research is very intriguing. My team is working on a project with possible privacy leakage. This isn't a field I know a whole lot about, but I'm very eager to learn more.

Would it be possible to meet some time to discuss your take on privacy in applications? Sydney shared [one of your projects](https://github.com/codingitforward/cdfdemoday2021/blob/main/Sarah_Birmingham.pdf) with me, and I would love to talk to you more about your approach! 

Hope to speak soon, take care.

Sincerely,
#privacy #data #addressing #formulas #algorithms 
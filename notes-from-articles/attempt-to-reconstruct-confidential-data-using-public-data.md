## Attempt tp reconstruct confidential data using public data 
>[!todo] What does decedent mean?

Ultimately, this was an investigation into [[differential-privacy]].

![[database-reconstruction-attack]]

- CFOI?
- Small quantities of data make reversibility very easy
- Published data available at the national level as well as per-state
- Author walks through first-approach problem rule structure from public data
	- Author admits that access to both public and confidential data is unrealistic for a real adversarial attack
	- Follows through with a [[cross-box]] style problem: categories are determined, and numbers are assigned
		- Not sure how numbers are determined, but then are iterated over until numbers run out
	- Ultimately this method is [[hand-coded]]
- Author walks through second-approach problem set where Google OR tools were used
- Author walks through third-approach problem set with 'merging permutations'
	- This occurs to the extent that within the 'final' group, there are all nine rule-based categories present in the data
	 - She determined this was too computationally expensive to pursue

| **categories used** |
| :---: |
| state | 
| event | 
| occupation | 
| industry |
| public/private |
| wage/self-employed | 
| gender |
| age category |
| race |


>[!todo] TO-DO
>What are OR-tools, and how might they be used in the context of BlueConduit? How was the model determined to be solved? How was it measured for accuracy? How was it measured for speed?

> [!summary] Summary and last thoughts
> The author proposed a final solution of combining back-tracking, OR-tools, and merged permutations. While this was still found to be expensive, the model was evaluated as 'solved', the checks for accuracy across all methods are not consistent, and leave questions remaining. 

##### Sources to follow up on:
- A. Narayanan, V. Shmatikov, "Robust De-anonymization of alre sparse datasets," *2008 IEEE Symposium of Security and Privacy (sp 2008)*, 2008, pp. 111-125, doi:10.1109/SP.2008.33
- S. Garfinkel, Abowd J.M, and Martindale C. 2018. "Understanding Reconstruction Attacks on Public Data," *Communications of the ACM,* 2018, vol. 62 no. 3, pp 43-46 (?), doi:10.1145/3287287
- Google OR Tools, Google Developers
- sarahbirmingham42@gmail.com


#data #privacy #blueconduit #articles #computer-science #machine-learning #SN


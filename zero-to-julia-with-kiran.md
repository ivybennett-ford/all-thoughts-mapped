---
title: Zero to Julia
author: Kiran Shila
publication-date: '2022:05:09'
tags:
  - julia
  - programming
  - SN
  - user-guide
---
## Julia with Automatic Differentiation
##### Purpose-built
- In Shila's talk, they identify a pressing need -- a programmer should know when to use a tool, and when to choose a different tool. 
- Part of being a good programmer implicates knowing the difference between use-cases

Multi-dimensional matrix in Julia
```julia
x = [1 2 3 4; 1 2 3 4]
```

```julia
% There are many ways to write functions

h(x) = x^2

function for all x in 1:10:
		y = x^2
	end
```

>"All named functions are generic"

- Forking is bad.

# Homework 1
## Usecases
**In your teams, think of some use cases of zero knowledge proofs What problems are there when using zkps in real world situations, such as providing an identity application for use in airports**

One of the use cases that I see in ZK tech is in verifiable credentials applications, and the possibility of selective disclosure or homomorphic operation to proof characteristics of their I inner claims. Also the identifiable credentials can be compatible with SBT(soulbound tokens) and de possibility of build compostable multiprotocol applications. One of the problems that i see is the computational cost of proofs generations it can be too computational expensive for low-end devices. In the specific application of prooving identity in airports, again, if the proof is computationaly expensive the prooving (proof generation + verification) time it will take long time and can bee counterproductive in crowded situations such airports.

## Maths Introduction

1. **Working with the following set of Integers S = {0,1,2,3,4,5,6,7,8} ,What is?**

	**a) 4 + 5** -> (4+5) mod(9) = 0 
	
	**b) 3 x 5** -> (3x5) mod(9) = 6
	
	
2. **For S = {0,1,2,3,4,5,6,7,8}**

		**Properties of a group G**
		Closure ∀ a ∈ G and b ∈ G -> a·b = c s.t. c ∈ G
	
		Associativity a·(b·c) = (b·a)·c 
	
		Identity element ∃ e ∈ G s.t. ∀ a ∈ G a·e=a
	
		Inverse element ∀ a ∈ G ∃ b ∈ G s.t. a·b=e		b=a^(-1) 
		

	**a) Can we consider 'S' and the operation multiplication to be a group?**
	
	No, because even though fulfills Closure and Assosiativity, the presence of the 0 element makes makes it not satisfy the other two properties, Identity (e for 0 is not the same e for the other elements) and Inverse (there is not an element a for 0 that 0·a=e).
	

	**b) Can we consider 'S' and the operation division to be a group?**
	
	No, because do not satisfy: 
	
	clousure, there are cases in which the division gives non integers numbers not presents in the group e.g. 1/2 ,
	
	associativity, (a/b)/c = a/(b·c) ≠ a/(b/c) = (a·c)/b,
	
	inverse element, for the 0 element we dont have inverse.
	
	however, identitiy element is fulfilled and being the identity 1 ∀ a ∈ G 
	
	
	
	
	
	
	
	
	
	
	
	

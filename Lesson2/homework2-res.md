# Homework 2
## Usecases
1. **Try out the vanity bitcoin address example at [asecurity](https://asecuritysite.com/blockchain/vanity) or the Ethereum [version](https://vanity-eth.tk/)**

2. **What do you understand by**

	1. **O(n)** : problems whose complexity (time or space it takes to solve) grows linearly with their numbers of inputs.
	2. **O(1)** : problems whose complexity do not grow with their number of inputs, constant complexity.
	3. **O(log(n))** : problems whose complexity grows logarithmically with their numbers of inputs.
	

3. **Which of those is best when describing a proof size**

	It depends to de zk system that we are talking about, being approx constant for SNARKs (O(1)) and polynomic (O(n^(k))  or logarithmic (O(log(n)) for other type of zk systems such STARKs.

4. **In your teams discuss why are there few identity projects on Starknet?**

	Maybe one of the reasons can be the change of paradigm in StarkNet respect Ethereum accounts model, new mechanics has to be thought to build identity projects over starknet.

	The Alpha state of StarkNet can be another reason, if the accounts model is susceptible to change, the mechanics to manage identities may change forcing projects to reformulate their solutions.

	By the way, for me, seems that an account abstraction can be more adequate for identity projects, because the identity authentication mechanics can be done directly on account contract allowing to put aside the need of having an Ethereum address as SSI (Self-sovereign identity) ID.


5. **In preparation for future lessons you need to install Protostar**
**See [documentation](https://docs.swmansion.com/protostar/docs/tutorials/installation) and this useful [medium article](https://blog.swmansion.com/testing-starknet-contracts-made-easy-with-protostar-2ecdad3c9133)**

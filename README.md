# Simple-Voting-Contract
A smart contract for a simple voting mechanism

The votYes() and voteNo() functions add the address of the voter to its respective array.
Can return the amount of votes in each category.

Note: if you wanted to return them both in a single string it's not that simple. Solidity does not provide an easy way to convert uints to strings so you could import the openzeppelin library: @openzeppelin/contracts/utils/Strings.sol
My suggestion would be to handle that on the front end though.

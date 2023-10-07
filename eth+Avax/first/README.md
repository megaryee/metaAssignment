# Car Contract

This is a Solidity smart contract that defines a car contract.

The car contract has two public variables: id and owner. 

The sellCar function takes an address _newowner as input and changes the owner of the car to _newowner.

The changeid function takes an unsigned integer _id as input and changes the id of the car to _id.

However, if _id is zero, the function will revert with an error message “id cannot be zero”. 

Additionally, only the owner of the car can change the id of the car 12.

## To use this contract, you can follow these steps:

Install Solidity on your machine.

Copy and paste the code into a new file.

Compile the code using Solidity.

Deploy the compiled code to your preferred blockchain network.

## Written by MegAryee

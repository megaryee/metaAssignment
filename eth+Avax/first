// SPDX-License-Identifier: MIT
pragma solidity 0.8.18;

contract car {

    uint public id;
    address public owner;
    
 // 0x0000000000000000000000000000000000000000  
function sellCar(address _newowner) public {
  assert (_newowner != address (0));
  owner = _newowner;  
}

function changeid(uint _id) public {
 if (_id == 0) {
     revert ("id cannot be zero");
 }

 require(msg.sender == owner, "only the owner can change the car id");

 id = _id;   
}

   
}

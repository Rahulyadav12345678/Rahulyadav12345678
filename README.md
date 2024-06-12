contract MyToken {

// public variables here

string public tokenName- "META";

string public tokenAbbrv - "ΜΤΑ";

uint public totalSupply = 0;

// mapping variable here

mapping(address => uint) public balances;

// mint function

function mint (address _address, uint_value) public {

totalSupply += _value;

balances[_address] +- _value;

}

// burn function

function burn (address _address, uint_value) public { if (balances[_address] >= _value) {

totalSupply_value; balances[_address] -- _value;

}

}

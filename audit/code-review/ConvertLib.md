# ConvertLib

Source file [../../contracts/ConvertLib.sol](../../contracts/ConvertLib.sol).

<br />

<hr />

```javascript
pragma solidity ^0.4.4;

library ConvertLib{
	function convert(uint amount,uint conversionRate) returns (uint convertedAmount)
	{
		return amount * conversionRate;
	}
}

```

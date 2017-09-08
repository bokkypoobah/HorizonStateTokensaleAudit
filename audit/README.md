# Horizon State Tokensale Audit

Status: To commence

## Summary

<br />

<hr />

## Table Of Contents

<br />

<hr />

## Recommendations

* **MEDIUM IMPORTANCE** `DecisionTokenSale.removeWhiteListedAddress(...)` should have the statement `whiteListedForPresale[buyer] = false;` instead of `whiteListedForPresale[buyer] = true;`

<br />

<hr />

## Code Review

* [ ] [code-review/ConvertLib.md](code-review/ConvertLib.md)
* [ ] [code-review/DecisionToken.md](code-review/DecisionToken.md)
  * [ ] contract DecisionToken is MintableToken 
* [ ] [code-review/DecisionTokenSale.md](code-review/DecisionTokenSale.md)
  * [ ] contract DecisionTokenSale is Ownable 

* [ ] [code-review/zeppelin/crowdsale/Crowdsale.md](code-review/zeppelin/crowdsale/Crowdsale.md)
  * [ ] contract Crowdsale
* [ ] [code-review/zeppelin/math/SafeMath.md](code-review/zeppelin/math/SafeMath.md)
* [ ] [code-review/zeppelin/ownership/Ownable.md](code-review/ownership/Ownable.md)
  * [ ] contract Ownable 
* [ ] [code-review/zeppelin/token/BasicToken.md](code-review/zeppelin/token/BasicToken.md)
  * [ ] contract BasicToken is ERC20Basic 
* [ ] [code-review/zeppelin/token/ERC20.md](code-review/zeppelin/token/ERC20.md)
  * [ ] contract ERC20 is ERC20Basic 
* [ ] [code-review/zeppelin/token/ERC20Basic.md](code-review/zeppelin/token/ERC20Basic.md)
  * [ ] contract ERC20Basic 
* [ ] [code-review/zeppelin/token/MintableToken.md](code-review/zeppelin/token/MintableToken.md)
  * [ ] contract MintableToken is StandardToken, Ownable 
* [ ] [code-review/zeppelin/token/StandardToken.md](code-review/zeppelin/token/StandardToken.md)
  * [ ] contract StandardToken is ERC20, BasicToken

<br />

### Not Reviewed

* [ ] [code-review/Migrations.md](code-review/Migrations.md)
  * [ ] contract Migrations

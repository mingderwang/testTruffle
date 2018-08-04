# test
```
truffle test
Using network 'development'.

Compiling ./contracts/DelegateV1.sol...
Compiling ./contracts/DelegateV2.sol...
Compiling ./contracts/KeyValueStorage.sol...
Compiling ./contracts/Migrations.sol...
Compiling ./contracts/Ownable.sol...
Compiling ./contracts/Proxy.sol...
Compiling ./contracts/SafeMath.sol...
Compiling ./contracts/StorageState.sol...

Compilation warnings encountered:

/Users/ming/src/ether/truffle/testTruffle/contracts/Proxy.sol:8:3: Warning: Defining constructors as functions with the same name as the contract is deprecated. Use "constructor(...) { ... }" instead.
  function Proxy(KeyValueStorage storage_ , address _owner) public {
  ^ (Relevant source part starts here and spans across multiple lines).
,/Users/ming/src/ether/truffle/testTruffle/contracts/Proxy.sol:25:5: Warning: Invoking events without "emit" prefix is deprecated.
    Upgraded(impl);
    ^------------^



  Contract: Storage and upgradability example
10
10
20
    ✓ should create and upgrade idap token (1584ms)


  1 passing (2s)
```

# refer to 
https://medium.com/quillhash/how-to-write-upgradable-smart-contracts-in-solidity-d8f1b95a0e9a

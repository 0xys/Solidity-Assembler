# Solidity Assembler

## Example code
```
push1 0x80
push1 0x40
mstore
callvalue
dup1
iszero
push @tag
jumpi
push1 0x00
dup1
revert
jumpdest @tag
pop
push1 0x40
mload
dup1
push1 0x01
swap1
mstore
push1 0x20
swap1
return
stop
```

```
npm start <FILE_PATH> 
608060405234801561001057600080fd5b506040518060019052602090f300
```
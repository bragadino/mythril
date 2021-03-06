# Analysis results for test-filename.sol

## Message call to external contract

- Type: Informational
- Contract: Unknown
- Function name: `_function_0x5a6814ec`
- PC address: 661

### Description

This contract executes a message call to to another contract. Make sure that the called contract is trusted and does not execute user-supplied code.

## Message call to external contract

- Type: Warning
- Contract: Unknown
- Function name: `_function_0xd24b08cc`
- PC address: 779

### Description

This contract executes a message call to an address found at storage slot 1. This storage slot can be written to by calling the function `_function_0x2776b163`. Generally, it is not recommended to call user-supplied adresses using Solidity's call() construct. Note that attackers might leverage reentrancy attacks to exploit race conditions or manipulate this contract's state.

## Message call to external contract

- Type: Informational
- Contract: Unknown
- Function name: `_function_0xe11f493e`
- PC address: 858

### Description

This contract executes a message call to to another contract. Make sure that the called contract is trusted and does not execute user-supplied code.

## State change after external call

- Type: Warning
- Contract: Unknown
- Function name: `_function_0xe11f493e`
- PC address: 869

### Description

The contract account state is changed after an external call. Consider that the called contract could re-enter the function before this state change takes place. This can lead to business logic vulnerabilities.

## Message call to external contract

- Type: Warning
- Contract: Unknown
- Function name: `_function_0xe1d10f79`
- PC address: 912

### Description

This contract executes a message call to an address provided as a function argument. Generally, it is not recommended to call user-supplied adresses using Solidity's call() construct. Note that attackers might leverage reentrancy attacks to exploit race conditions or manipulate this contract's state.

## Transaction order dependence

- Type: Warning
- Contract: Unknown
- Function name: `_function_0xd24b08cc`
- PC address: 779

### Description

A possible transaction order independence vulnerability exists in function _function_0xd24b08cc. The value or direction of the call statement is determined from a tainted storage location

## Unchecked CALL return value

- Type: Informational
- Contract: Unknown
- Function name: `_function_0x5a6814ec`
- PC address: 661

### Description

The return value of an external call is not checked. Note that execution continue even if the called contract throws.

## Unchecked CALL return value

- Type: Informational
- Contract: Unknown
- Function name: `_function_0xd24b08cc`
- PC address: 779

### Description

The return value of an external call is not checked. Note that execution continue even if the called contract throws.

## Unchecked CALL return value

- Type: Informational
- Contract: Unknown
- Function name: `_function_0xe11f493e`
- PC address: 858

### Description

The return value of an external call is not checked. Note that execution continue even if the called contract throws.

## Unchecked CALL return value

- Type: Informational
- Contract: Unknown
- Function name: `_function_0xe1d10f79`
- PC address: 912

### Description

The return value of an external call is not checked. Note that execution continue even if the called contract throws.
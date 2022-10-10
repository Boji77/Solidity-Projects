# Solidity-Projects

As I am learning solidity and EVM compatible smart contracts, I built this lottery contract for fun

Lottery entry fee should be more than 0.1 ETH

The admin terminates the lottery round by choosing a random winner

To fulfill randomness, chainlink consumer base contract is called to provide a truly verifiable random number

This then creates a chain reaction calling multiple functions until a winner is paid the full ETH amount stored in the smart contract

The sample contract to pick a random number from chainlink is also provided
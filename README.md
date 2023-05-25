# Foundry-withCorrectConfig

Getting Foundry to work with relevant dependencies can be tricky.

I have created this repository that configures Foundry with upgradeable OpenZeppelin libraries.

This way, it provides a solid foundation for smart contract auditors and developers to start with and build upon.

OpenZeppelin libraries are configured with node_modules and forge-std under lib. 
Both are correctly configured for the script/src/test files thanks to remappings. 
Please refer to remappings.txt for details

Some protocols include older OpenZeppelin contracts, while others incorporate new upgradeable OpenZeppelin contracts. 
This typically applies to older protocols that have updated their contracts. 
To ensure smooth synchronization of all files, a combination of older OpenZeppelin contracts and newer upgradeable OpenZeppelin contracts 
need to be imported.

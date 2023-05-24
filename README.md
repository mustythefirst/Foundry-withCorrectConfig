# Foundry-withCorrectConfig

Getting Foundry to work with relevant dependencies can be tricky.

I have created this repository that configures Foundry with upgradeable OpenZeppelin libraries.

This way, it provides a solid foundation for smart contract auditors and developers to start with and build upon.

OpenZeppelin libraries are configured with node_modules and forge-std under lib. 
Both are correctly configured for the script/src/test files thanks to remappings. 
Please refer to remappings.txt for details

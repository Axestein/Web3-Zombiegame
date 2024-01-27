# ZombieFactory Contract

Description:

This Solidity contract serves as a foundation for a simple zombie-themed game on the Ethereum blockchain.
It enables the creation of zombies with unique names and DNA, and it emits events to signal their creation.
Features:

Zombie Creation:
createRandomZombie(string memory _name): Generates a zombie with a random DNA and the given name.
DNA Generation:
_generateRandomDna(string memory _str): Calculates a random DNA based on a string input, ensuring unique zombies.
Event Emission:
NewZombie: Emitted when a new zombie is created, providing its ID, name, and DNA for external interactions.
Usage:

Deploy the contract to an Ethereum network.
Interact with the createRandomZombie function to create new zombies.
Listen for the NewZombie event to track zombie creation and react accordingly.
Files:

ZombieFactory.sol: Contains the Solidity code for the contract.
README.md: This file (you're reading it now!).
Dependencies:

Solidity compiler (e.g., solc)
Ethereum development environment (e.g., Remix, Truffle, Hardhat)
Web3 library for interacting with the contract
Author:

Aditya Kumar singh

Contributions:

Pull requests are welcome! Please follow the project's coding style and conventions.

Contact:

For questions or feedback, contact [adityandmb@gmail.com].

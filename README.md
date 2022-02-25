# Solidity workshops

Lesson 0. Introduction to blockchain concepts (what is what, consensus, transactions, wallets, nodes, web3)

Lesson 1. First chapter of CryptoZombies (math, structs, functions, visibility, msg.sender, SafuDot)

Lesson 2. Using git (git.hsbp.org, git command, init, add, commit, pull, push, using git issues)

Lesson 3. Second chapter of CryptoZombies (return, mappings, require, inheritance, import, interfaces, multi return, keccak if str

Lesson 4. TBA


## Notes

    Return-ok if utan, megbeszelni: if utani return es revert.
    https://git.hsbp.org/flamboush/Balazs_Homework_1/src/branch/master/product_reviews_contract.sol

    mapping(_KeyType => _ValueType) public mappingName
    mapping(address => uint) public playerLevel;
    ! mapping can be inside struct
    ! nested mappings
      mapping(uint => mapping(uint => uint)) mymap;
      mymap [1][1] = 42;

## HW for now

    - Create multiple an external function that returns two uint256s based on user input (true or fale).
    - Call function of adminChange() of SafuDot from a smart contract
    - Create a new repository on git.hsbp.org with the name "Homework 2 - <your_name>" and add your homework to it.
    - Remember to create a README.md and LICENSE to your git repository!

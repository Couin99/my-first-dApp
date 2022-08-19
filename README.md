# my-first-dApp

//SPDX-Licence-Identifier: MIT
pragma solidity ^0.8.1;

/// a simple set and get functionn for mood defined

//define the contract
contract MoodDiary{

    //create a variable called mood
    string mood;

    //create a function that writes a mood to the smart contract
    function setMood(string memory_mood) public{
        mood = _mood;
    }

    //create a function that reads the mood from the smart contract
    function getMood() public view returns (string memory){
        return mood;
    }
}

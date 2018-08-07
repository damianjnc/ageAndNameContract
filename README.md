pragma solidity ^0.4.0;

contract myAgeAndName {
    
    uint output;
    
    function getAge() view returns(uint){ return 
        output;
    }
    
    string outputName;
    function getName() view returns(string){
        return outputName;
    }
    
    function setAge(uint _output){
        output=_output;
        
    }
    
    function setName(string _outputName){
        outputName=_outputName;
    }
    
}

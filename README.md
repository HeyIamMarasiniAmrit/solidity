Solidity is an object-oriented, high-level language for implementing smart contracts. Smart contracts are programs that govern the behavior of accounts within the Ethereum state.

Contract
A Solidity contract is a collection of code (its functions) and data (its state) that resides at a specific address on the Ethereumblockchain.

The line uintstoredData declares a state variable called storedData of type uint and the functions set and get can be used to modify or retrieve the value of the variable.

Importing Files
Though above example does not have an import statement but Solidity supports import statements that are very similar to those available in JavaScript.

The following statement imports all global symbols from "filename".

Solidity - Comments
Any text between a // and the end of a line is treated as a comment and is ignored by Solidity Compiler.

Any text between the characters /* and */ is treated as a comment. This may span multiple lines.

Solidity - Types
While writing program in any language, you need to use various variables to store various information. Variables are nothing but reserved memory locations to store values. This means that when you create a variable you reserve some space in memory.

You may like to store information of various data types like character, wide character, integer, floating point, double floating point, boolean etc. Based on the data type of a variable, the operating system allocates memory and decides what can be stored in the reserved memory.

Solidity - Variables
State Variables − Variables whose values are permanently stored in a contract storage.

Local Variables − Variables whose values are present till function is executing.

Scope of local variables is limited to function in which they are defined but State variables can have three types of scopes.

Public − Public state variables can be accessed internally as well as via messages. For a public state variable, an automatic getter function is generated.

Internal − Internal state variables can be accessed only internally from the current contract or contract deriving from it without using this.

Private − Private state variables can be accessed only internally from the current contract they are defined not in the derived contract from it.

Global Variables − Special variables exists in the global namespace used to get information about the blockchain.
Local Variable
Variables whose values are available only within a function where it is defined. Function parameters are always local to that function.
Global Variables
These are special variables which exist in global workspace and provide information about the blockchain and transaction properties.

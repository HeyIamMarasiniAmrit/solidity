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
🚀 Why Blockchain Technology Matters in 2025 🔗
In today’s world of digital transformation, trust and transparency are more important than ever. That’s where blockchain technology comes in.
✅ Decentralized: No single point of control
 ✅ Transparent: Everyone can verify transactions
 ✅ Secure: Tamper-proof due to cryptography
 ✅ Efficient: Reduces need for intermediaries
Blockchain is not just for crypto. It's revolutionizing:
Supply Chains 🌐 (Track goods from factory to shelf)
Healthcare 🏥 (Secure medical records)
Finance 💰 (Smart contracts and DeFi)
Voting Systems 🗳️ (Tamper-resistant elections)
💡 Here's a simple Solidity smart contract example: a basic wallet that stores and transfers ETH.
👨‍💻 Built with Solidity – the language of Ethereum smart contracts.

Scope of local variables is limited to function in which they are defined but State variables can have three types of scopes.

Public − Public state variables can be accessed internally as well as via messages. For a public state variable, an automatic getter function is generated.

Internal − Internal state variables can be accessed only internally from the current contract or contract deriving from it without using this.

Private − Private state variables can be accessed only internally from the current contract they are defined not in the derived contract from it.

Global Variables − Special variables exists in the global namespace used to get information about the blockchain.
Local Variable
Variables whose values are available only within a function where it is defined. Function parameters are always local to that function.
Global Variables
These are special variables which exist in global workspace and provide information about the blockchain and transaction properties.

Arithmetic Operators
Solidity supports the following arithmetic operators −

Assume variable A holds 10 and variable B holds 20, then −

Show Example

Sr.No.	Operator & Description
1	
+ (Addition)

Adds two operands

Ex: A + B will give 30

2	
- (Subtraction)

Subtracts the second operand from the first

Ex: A - B will give -10

3	
* (Multiplication)

Multiply both operands

Ex: A * B will give 200

4	
/ (Division)

Divide the numerator by the denominator

Ex: B / A will give 2

5	
% (Modulus)

Outputs the remainder of an integer division

Ex: B % A will give 0

6	
++ (Increment)

Increases an integer value by one

Ex: A++ will give 11

7	
-- (Decrement)

Decreases an integer value by one

Ex: A-- will give 9

Comparison Operators
Solidity supports the following comparison operators −

Assume variable A holds 10 and variable B holds 20, then −

Show Example

Sr.No.	Operator & Description
1	
= = (Equal)

Checks if the value of two operands are equal or not, if yes, then the condition becomes true.

Ex: (A == B) is not true.

2	
!= (Not Equal)

Checks if the value of two operands are equal or not, if the values are not equal, then the condition becomes true.

Ex: (A != B) is true.

3	
> (Greater than)

Checks if the value of the left operand is greater than the value of the right operand, if yes, then the condition becomes true.

Ex: (A > B) is not true.

4	
< (Less than)

Checks if the value of the left operand is less than the value of the right operand, if yes, then the condition becomes true.

Ex: (A < B) is true.

5	
>= (Greater than or Equal to)

Checks if the value of the left operand is greater than or equal to the value of the right operand, if yes, then the condition becomes true.

Ex: (A >= B) is not true.

6	
<= (Less than or Equal to)

Checks if the value of the left operand is less than or equal to the value of the right operand, if yes, then the condition becomes true.

Ex: (A <= B) is true.

Logical Operators
Solidity supports the following logical operators −

Assume variable A holds 10 and variable B holds 20, then −

Show Example

Sr.No.	Operator & Description
1	
&& (Logical AND)

If both the operands are non-zero, then the condition becomes true.

Ex: (A && B) is true.

2	
|| (Logical OR)

If any of the two operands are non-zero, then the condition becomes true.

Ex: (A || B) is true.

3	
! (Logical NOT)

Reverses the logical state of its operand. If a condition is true, then the Logical NOT operator will make it false.

Ex: ! (A && B) is false.

Bitwise Operators
Solidity supports the following bitwise operators −

Assume variable A holds 2 and variable B holds 3, then −

Show Example

Sr.No.	Operator & Description
1	
& (Bitwise AND)

It performs a Boolean AND operation on each bit of its integer arguments.

Ex: (A & B) is 2.

2	
| (BitWise OR)

It performs a Boolean OR operation on each bit of its integer arguments.

Ex: (A | B) is 3.

3	
^ (Bitwise XOR)

It performs a Boolean exclusive OR operation on each bit of its integer arguments. Exclusive OR means that either operand one is true or operand two is true, but not both.

Ex: (A ^ B) is 1.

4	
~ (Bitwise Not)

It is a unary operator and operates by reversing all the bits in the operand.

Ex: (~B) is -4.

5	
<< (Left Shift)

It moves all the bits in its first operand to the left by the number of places specified in the second operand. New bits are filled with zeros. Shifting a value left by one position is equivalent to multiplying it by 2, shifting two positions is equivalent to multiplying by 4, and so on.

Ex: (A << 1) is 4.

6	
>> (Right Shift)

Binary Right Shift Operator. The left operand's value is moved right by the number of bits specified by the right operand.

Ex: (A >> 1) is 1.

7	
>>> (Right shift with Zero)

This operator is just like the >> operator, except that the bits shifted in on the left are always zero.

Ex: (A >>> 1) is 1.

Assignment Operators
Solidity supports the following assignment operators −

Show Example

Sr.No.	Operator & Description
1	
= (Simple Assignment )

Assigns values from the right side operand to the left side operand

Ex: C = A + B will assign the value of A + B into C

2	
+= (Add and Assignment)

It adds the right operand to the left operand and assigns the result to the left operand.

Ex: C += A is equivalent to C = C + A

3	
−= (Subtract and Assignment)

It subtracts the right operand from the left operand and assigns the result to the left operand.

Ex: C -= A is equivalent to C = C - A

4	
*= (Multiply and Assignment)

It multiplies the right operand with the left operand and assigns the result to the left operand.

Ex: C *= A is equivalent to C = C * A

5	
/= (Divide and Assignment)

It divides the left operand with the right operand and assigns the result to the left operand.

Ex: C /= A is equivalent to C = C / A

6	
%= (Modules and Assignment)

It takes modulus using two operands and assigns the result to the left operand.

Ex: C %= A is equivalent to C = C % A

Note − Same logic applies to Bitwise operators so they will become like <<=, >>=, >>=, &=, |= and ^=.

Conditional Operator (? :)
The conditional operator first evaluates an expression for a true or false value and then executes one of the two given statements depending upon the result of the evaluation.

Solidity - Loops
While writing a contract, you may encounter a situation where you need to perform an action over and over again. In such situations, you would need to write loop statements to reduce the number of lines.

Solidity supports all the necessary loops to ease down the pressure of programming.

Sr.No	Loops & Description
1	
While Loop

The most basic loop in Solidity is the while loop which would be discussed in this chapter.

2	
do...while Loop

The do...while loop is similar to the while loop except that the condition check happens at the end of the loop.

3	
For Loop

The for loop is the most compact form of looping. It includes the following three important parts.

4	
Loop Control

Solidity provides full control to handle loops and switch statements.
Solidity - While Loop
The most basic loop in Solidity is the while loop which would be discussed in this chapter. The purpose of a while loop is to execute a statement or code block repeatedly as long as an expression is true. Once the expression becomes false, the loop terminates.
Syntax
The syntax of while loop in Solidity is as follows −

while (expression) {
   Statement(s) to be executed if expression is true
}
Solidity - do...while loop
The do...while loop is similar to the while loop except that the condition check happens at the end of the loop. This means that the loop will always be executed at least once, even if the condition is false.
Syntax
The syntax for do-while loop in Solidity is as follows −

do {
   Statement(s) to be executed;
} while (expression);
Solidity - For Loop
The for loop is the most compact form of looping. It includes the following three important parts −

The loop initialization where we initialize our counter to a starting value. The initialization statement is executed before the loop begins.

The test statement which will test if a given condition is true or not. If the condition is true, then the code given inside the loop will be executed, otherwise the control will come out of the loop.

The iteration statement where you can increase or decrease your counter.

You can put all the three parts in a single line separated by semicolons.
Solidity - Decision Making
While writing a program, there may be a situation when you need to adopt one out of a given set of paths. In such cases, you need to use conditional statements that allow your program to make correct decisions and perform right actions.

Solidity supports conditional statements which are used to perform different actions based on different conditions. Here we will explain the if..else statement.
Solidity - if statement
The if statement is the fundamental control statement that allows Solidity to make decisions and execute statements conditionally.

Syntax
The syntax for a basic if statement is as follows −

if (expression) {
   Statement(s) to be executed if expression is true
}
Here a Solidity expression is evaluated. If the resulting value is true, the given statement(s) are executed. If the expression is false, then no statement would be not executed. Most of the times, you will use comparison operators while making decisions.
Solidity - if...else statement
The 'if...else' statement is the next form of control statement that allows Solidity to execute statements in a more controlled way.

Syntax
if (expression) {
   Statement(s) to be executed if expression is true
} else {
   Statement(s) to be executed if expression is false
}
Solidity - if...else if... statement.
The if...else if... statement is an advanced form of if...else that allows Solidity to make a correct decision out of several conditions.

Syntax
The syntax of an if-else-if statement is as follows −

if (expression 1) {
   Statement(s) to be executed if expression 1 is true
} else if (expression 2) {
   Statement(s) to be executed if expression 2 is true
} else if (expression 3) {
   Statement(s) to be executed if expression 3 is true
} else {
   Statement(s) to be executed if no expression is true
}
There is nothing special about this code. It is just a series of if statements, where each if is a part of the else clause of the previous statement. Statement(s) are executed based on the true condition, if none of the conditions is true, then the else block is executed.

Solidity - Strings
Solidity supports String literal using both double quote (") and single quote ('). It provides string as a data type to declare a variable of type String.

pragma solidity ^0.5.0;

contract SolidityTest {
   string data = "test";
}
In above example, "test" is a string literal and data is a string variable. More preferred way is to use byte types instead of String as string operation requires more gas as compared to byte operation. Solidity provides inbuilt conversion between bytes to string and vice versa. In Solidity we can assign String literal to a byte32 type variable easily. Solidity considers it as a byte32 literal.

Solidity - Strings
Solidity supports String literal using both double quote (") and single quote ('). It provides string as a data type to declare a variable of type String.

pragma solidity ^0.5.0;

contract SolidityTest {
   string data = "test";
}
In above example, "test" is a string literal and data is a string variable. More preferred way is to use byte types instead of String as string operation requires more gas as compared to byte operation. Solidity provides inbuilt conversion between bytes to string and vice versa. In Solidity we can assign String literal to a byte32 type variable easily. Solidity considers it as a byte32 literal.
Solidity - Arrays
Array is a data structure, which stores a fixed-size sequential collection of elements of the same type. An array is used to store a collection of data, but it is often more useful to think of an array as a collection of variables of the same type.

Instead of declaring individual variables, such as number0, number1, ..., and number99, you declare one array variable such as numbers and use numbers[0], numbers[1], and ..., numbers[99] to represent individual variables. A specific element in an array is accessed by an index.

In Solidity, an array can be of compile-time fixed size or of dynamic size. For storage array, it can have different types of elements as well. In case of memory array, element type can not be mapping and in case it is to be used as function parameter then element type should be an ABI type.

All arrays consist of contiguous memory locations. The lowest address corresponds to the first element and the highest address to the last element.

Declaring Arrays
To declare an array of fixed size in Solidity, the programmer specifies the type of the elements and the number of elements required by an array as follows −

type arrayName [ arraySize ];
This is called a single-dimension array. The arraySize must be an integer constant greater than zero and type can be any valid Solidity data type. For example, to declare a 10-element array called balance of type uint, use this statement −

uint balance[10];
To declare an array of dynamic size in Solidity, the programmer specifies the type of the elements as follows −

type[] arrayName;
Initializing Arrays
You can initialize Solidity array elements either one by one or using a single statement as follows −

uint balance[3] = [1, 2, 3];
The number of values between braces [ ] can not be larger than the number of elements that we declare for the array between square brackets [ ]. Following is an example to assign a single element of the array −

If you omit the size of the array, an array just big enough to hold the initialization is created. Therefore, if you write −

uint balance[] = [1, 2, 3];
You will create exactly the same array as you did in the previous example.

balance[2] = 5;
The above statement assigns element number 3rd in the array a value of 5.

Creating dynamic memory arrays
Dynamic memory arrays are created using new keyword.

uint size = 3;
uint balance[] = new uint[](size);
Accessing Array Elements
An element is accessed by indexing the array name. This is done by placing the index of the element within square brackets after the name of the array. For example −

uint salary = balance[2];
The above statement will take 3rd element from the array and assign the value to salary variable. Following is an example, which will use all the above-mentioned three concepts viz. declaration, assignment and accessing arrays −
Solidity - Enums
Enums restrict a variable to have one of only a few predefined values. The values in this enumerated list are called enums.

With the use of enums it is possible to reduce the number of bugs in your code.

For example, if we consider an application for a fresh juice shop, it would be possible to restrict the glass size to small, medium, and large. This would make sure that it would not allow anyone to order any size other than small, medium, or large.

Example
Try the following code to understand how the enum works in Solidity.

pragma solidity ^0.5.0;

contract test {
   enum FreshJuiceSize{ SMALL, MEDIUM, LARGE }
   FreshJuiceSize choice;
   FreshJuiceSize constant defaultChoice = FreshJuiceSize.MEDIUM;

   function setLarge() public {
      choice = FreshJuiceSize.LARGE;
   }
   function getChoice() public view returns (FreshJuiceSize) {
      return choice;
   }
   function getDefaultChoice() public pure returns (uint) {
      return uint(defaultChoice);
   }
}
Run the above program using steps provided in Solidity First Application chapter.
Solidity - Structs
Struct types are used to represent a record. Suppose you want to keep track of your books in a library. You might want to track the following attributes about each book −

Title
Author
Subject
Book ID
Defining a Struct
To define a Struct, you must use the struct keyword. The struct keyword defines a new data type, with more than one member. The format of the struct statement is as follows −

struct struct_name { 
   type1 type_name_1;
   type2 type_name_2;
   type3 type_name_3;
}
Example
struct Book { 
   string title;
   string author;
   uint book_id;
}
Accessing a Struct and its variable
To access any member of a structure, we use the member access operator (.). The member access operator is coded as a period between the structure variable name and the structure member that we wish to access. You would use the struct to define variables of structure type. The following example shows how to use a structure in a program.

Example
Try the following code to understand how the structs works in Solidity.

pragma solidity ^0.5.0;

contract test {
   struct Book { 
      string title;
      string author;
      uint book_id;
   }
   Book book;

   function setBook() public {
      book = Book('Learn Java', 'TP', 1);
   }
   function getBookId() public view returns (uint) {
      return book.book_id;
   }
}
Solidity - Mapping
Mapping is a reference type as arrays and structs. Following is the syntax to declare a mapping type.

mapping(_KeyType => _ValueType)
Where

_KeyType − can be any built-in types plus bytes and string. No reference type or complex objects are allowed.

_ValueType − can be any type.

Considerations
Mapping can only have type of storage and are generally used for state variables.

Mapping can be marked public. Solidity automatically create getter for it.

Example
Try the following code to understand how the mapping type works in Solidity.

pragma solidity ^0.5.0;

contract LedgerBalance {
   mapping(address => uint) public balances;

   function updateBalance(uint newBalance) public {
      balances[msg.sender] = newBalance;
   }
}
contract Updater {
   function updateBalance() public returns (uint) {
      LedgerBalance ledgerBalance = new LedgerBalance();
      ledgerBalance.updateBalance(10);
      return ledgerBalance.balances(address(this));
   }
}
Run the above program using steps provided in Solidity First Application chapter.

First Click updateBalance Button to set the value as 10 then look into the logs which will show the decoded output as −

Output
{
   "0": "uint256: 10"
}
Solidity - Conversions
Solidity allows implicit as well as explicit conversion. Solidity compiler allows implicit conversion between two data types provided no implicit conversion is possible and there is no loss of information. For example uint8 is convertible to uint16 but int8 is convertible to uint256 as int8 can contain negative value not allowed in uint256.

Explicit Conversion
We can explicitly convert a data type to another using constructor syntax.

int8 y = -3;
uint x = uint(y);
//Now x = 0xfffff..fd == two complement representation of -3 in 256 bit format.
Conversion to smaller type costs higher order bits.

uint32 a = 0x12345678;
uint16 b = uint16(a); // b = 0x5678
Conversion to higher type adds padding bits to the left.

uint16 a = 0x1234;
uint32 b = uint32(a); // b = 0x00001234 
Conversion to smaller byte costs higher order data.

bytes2 a = 0x1234;
bytes1 b = bytes1(a); // b = 0x12
Conversion to larger byte add padding bits to the right.

bytes2 a = 0x1234;
bytes4 b = bytes4(a); // b = 0x12340000
Conversion between fixed size bytes and int is only possible when both are of same size.

bytes2 a = 0x1234;
uint32 b = uint16(a); // b = 0x00001234
uint32 c = uint32(bytes4(a)); // c = 0x12340000
uint8 d = uint8(uint16(a)); // d = 0x34
uint8 e = uint8(bytes1(a)); // e = 0x12
Hexadecimal numbers can be assigned to any integer type if no truncation is needed.

Solidity - Ether Units
In solidity we can use wei, finney, szabo or ether as a suffix to a literal to be used to convert various ether based denominations. Lowest unit is wei and 1e12 represents 1 x 1012.

Time Units
Similar to currency, Solidity has time units where lowest unit is second and we can use seconds, minutes, hours, days and weeks as suffix to denote time.

Solidity - Special Variables
Special variables are globally available variables and provides information about the blockchain. Following is the list of special variables −

Sr.No.	Special Variable & Description
1	
blockhash(uint blockNumber) returns (bytes32)

Hash of the given block - only works for 256 most recent, excluding current, blocks.

2	
block.coinbase (address payable)

Current block miner's address.

3	
block.difficulty (uint)

current block difficulty.

4	
block.gaslimit (uint)

Current block gaslimit.

5	
block.number (uint)

Current block number.

6	
block.timestamp

Current block timestamp as seconds since unix epoch.

7	
gasleft() returns (uint256)

Remaining gas.

8	
msg.data (bytes calldata)

Complete calldata.

9	
msg.sender (address payable)

Sender of the message (current call).

10	
msg.sig (bytes4)

First four bytes of the calldata (i.e. function identifier)

11	
msg.value (uint)

Number of wei sent with the message.

12	
now (uint)

Current block timestamp (alias for block.timestamp).

13	
tx.gasprice (uint)

Gas price of the transaction.

14	
tx.origin (address payable)

Sender of the transaction (full call chain).

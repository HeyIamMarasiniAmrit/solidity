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

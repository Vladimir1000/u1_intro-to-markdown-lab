# Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. Basic syntax
`
const functionName = (params) => {
  // code to be executed
}
`
* **const**: const should be used whenever a function expression is assigned to a variable.
* **The function name**: The name you choose for the function.
* **Parameter**s: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
* **The arrow syntax**: Indicates that this will be a function.
* **The body**: The statements that make up the function itself. Surrounded by curly braces.

***Example***:
`
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
`
>Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. 
>>Examples include fetchData( ), calculateArea( ), or printReport( ). 

## 2. Calling a function

To execute the function, you _call_ or _invoke_ it by using its name followed by parentheses.

***Example***:

`greet('Alice'); // Outputs: Hello, Alice!`

## 3. Return values

Functions can process data input and output a value using the **return** keyword.

***Example***: 

`const addNums = (numA, numB) => {
  return numA + numB
}
const total = addNums(2, 4);`

`console.log(total) // Expected value: 6`

For more information on functions and how they are used in JS, check out the [MDN docs.](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

![Matrix Code](./markus-spiske-iar-afB0QQw-unsplash.jpg)

### Part 2 of the Markdown Lab

# How to Create a File Using the Terminal

In this tutorial, you'll learn how to create a new file using the Terminal or Command Prompt on your operating system. This method allows you to quickly create files without using a graphical user interface.

## Requirements

Before you begin, make sure that you have access to a Terminal or Command Prompt on your system. This tutorial assumes you have basic knowledge of computers

## Step 1: Open the Terminal or Command Prompt

First, open your Terminal or Command Prompt. You can typically find these applications in your system's utilities folder or by searching for "Terminal" (Mac/Linux) or "Command Prompt" (Windows) in the system search bar.

## Step 2: Navigate to the Desired Directory

Navigate to the directory where you want to create the new file. You can use the `cd` command to change directories. For example, to navigate to the Desktop directory, you would use:

```bash
cd Desktop
```
### Other usefull commands to change directories:
* To return to the home directory immediately, use 
```bash 
cd ~ OR cd
```
* To change into the root directory of Linux file system, use
```bash
 cd /.
 ```
* To go into the root user directory, run
```bash
 cd /root/
 ```
* To navigate up one directory level up, use
```bash
 cd ..
 ```
* To go back to the previous directory, use 
```bash
cd -
```
## Step 3: Use the mkdir Command to create a new directory or folder
Use the mkdir command followed by the desired folder name to create a new fodler. For example, to create a file folder named new folder, you would use:
```bash
mkdir new folder
```

## Step 4: Use the touch Command to create a new file using the terminal

Use the touch command followed by the desired file name to create a new file. For example, to create a file named example.txt, you would use:
```bash
touch example.txt
```
## Step 5: Verify that the created file or folder exist oi our directory
To verify that the file/folder was created successfully, you can list the files in the current directory using the commands:
```bash
ls or ls -a
```
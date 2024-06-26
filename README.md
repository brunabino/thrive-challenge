# Thrive Code Challenge

## Description
I completed the challenge using Node.js and created a contract test to verify the solution's correctness. The contract test ensures that the data meets the specified criteria, and I'll explain this in detail in the following sections.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Node.js:** This project requires Node.js. If you don't have it installed, you can download it from [here](https://nodejs.org/).
   ```shell
   Node.js version: v20.12.1
    ```
- **Jest:** Jest is required to make a contract test

    ```shell
   npm install jest --save-dev
    ```

## Running the Solution

To run the solution, execute the following command:

   
```shell
node challenge.js
```

To run the contract test, use:


```shell
npm test
```

## Contract Test
The contract test can be found in the challenge.test.js file located in the test folder. I chose to use Jest because I am familiar with it, and it provides a robust framework for writing and running tests. The test ensures that the challenge data adheres to the specified criteria.

## Solution Explanation
For this challenge, I used Node.js to process the data and meet all the criteria outlined in the challenge. The solution involves:

* Sorting: I sorted the user data by last name, and then by first name in case of duplicate last names. This ensures that users are listed in a consistent and expected order.
* Filtering: Users are filtered based on their active status and email status, in conjunction with the company's email status.
* Output: Only companies with associated users are printed. This avoids printing companies with no users, ensuring the output is concise and relevant.
* Top-Up Calculation: The total amount of top-ups for each company is calculated based on the company's top-up value and the number of users that receive the top-up.

By structuring the code this way, I ensured clarity and maintainability while meeting the challenge requirements.

Enjoy! 🚀

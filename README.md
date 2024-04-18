## Node.js Jest Testing

This repository serves as the solution to a [task](https://github.com/AlreadyBored/nodejs-assignments/blob/main/assignments/basic-testing/assignment.md) writing unit tests using the Jest API. 


### How to run

```bash
# run unit tests
$ npm run test

# with logging
$ npm run test:verbose
```

#### **Simple tests**

`src/01-simple-tests/index.test.ts`

Write unit tests for the `simpleCalculator` function, which performs basic mathematical operations - addition, subtraction, division, multiplication, and exponentiation. Your task is to verify that the operations are executed correctly and that the function returns `null` for invalid input.

---

#### **Table tests**

`src/02-table-tests/index.test.ts`

Rewrite the tests written in the previous task using the table-driven testing approach, utilizing the appropriate Jest API.

---


#### **Error handling & async**

`src/03-error-handling-async/index.test.ts`

Test functions that work asynchronously/throw/reject exceptions.

---

#### **Testing class**

`src/04-test-class/index.test.ts`

Test a class representing a bank account that implements corresponding operations.

---

#### **Partial mocking**

`src/05-partial-mocking/index.test.ts`

Utilize the Jest API to partially mock the contents of a module.

---

#### **Mocking Node.js API**

`src/06-mocking-node-api/index.test.ts`

Test the proper usage of the Node.js API based on commonly used APIs such as the `fs` module, as well as `setTimeout` and `setInterval`.

---

#### **Mocking library API**

`src/07-mocking-lib-api/index.test.ts`

Test the function that utilize library APIs is working correctly (with commonly used libraries such as `axios` and `lodash`).

---

#### **Snapshot testing**

`src/08-snapshot-testing/index.test.ts`

Use snapshot testing with Jest and compare it to regular comparison testing.
# ALX Backend JavaScript - ES6 Promises

This project is focused on understanding and working with ES6 Promises in JavaScript. The tasks involve creating and handling promises, managing errors, and ensuring the correct execution flow with asynchronous code.

## Tasks Overview

### 0. Keep every promise you make and only make promises you can keep
- **File:** `0-promise.js`
- **Description:** Return a `Promise` from the function `getResponseFromAPI()`.

### 1. Don't make a promise...if you know you can't keep it
- **File:** `1-promise.js`
- **Description:** Return a `Promise` from `getFullResponseFromAPI(success)`. If `success` is true, resolve with an object `{status: 200, body: 'Success'}`. If `false`, reject with an error object `{message: 'The fake API is not working currently'}`.

### 2. Catch me if you can!
- **File:** `2-then.js`
- **Description:** Append handlers to a `Promise` to log and handle the response from the API.

### 3. Handle multiple successful promises
- **File:** `3-all.js`
- **Description:** Import `uploadPhoto` and `createUser`, then collectively resolve all promises and log the results.

### 4. Simple promise
- **File:** `4-user-promise.js`
- **Description:** Create a function `signUpUser` that returns a resolved promise with the user's first and last name.

### 5. Reject the promises
- **File:** `5-photo-reject.js`
- **Description:** Create a function `uploadPhoto` that returns a rejected promise with an error message based on the filename.

### 6. Handle multiple promises
- **File:** `6-final-user.js`
- **Description:** Use `signUpUser` and `uploadPhoto` to handle multiple promises and return their statuses and results in an array.

### 7. Load balancer
- **File:** `7-load_balancer.js`
- **Description:** Create a function `loadBalancer` that returns the value of the first resolved promise between two provided promises.

### 8. Throw error / try catch
- **File:** `8-try.js`
- **Description:** Create a function `divideFunction` that throws an error if the denominator is zero, otherwise returns the division result.

### 9. Throw an error
- **File:** `9-try.js`
- **Description:** Create a function `guardrail` that handles errors from a provided function and appends the result or error message to an array.

## How to Use

1. **Install Dependencies:**
   ```bash
         npm install

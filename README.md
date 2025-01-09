# React Native FlatList Bug: Invalid Data Source or keyExtractor

This repository demonstrates a common error encountered when using the FlatList component in React Native: issues related to the data source and `keyExtractor` function.  The `bug.js` file shows an example of incorrectly formatted data leading to rendering errors or crashes. The `bugSolution.js` file demonstrates the correct implementation, providing a properly structured data source and a functional `keyExtractor`.

## How to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run the app using a React Native development environment (e.g., Expo).
4. Observe the rendering errors in `bug.js` and the correct rendering in `bugSolution.js`.

## Solution

The core issue lies in providing correctly formatted data to FlatList and implementing a robust `keyExtractor` function.  Make sure your data is an array of objects, each with a unique key, and use `keyExtractor` to properly extract the unique identifier from each object.  Refer to `bugSolution.js` for a clear example.
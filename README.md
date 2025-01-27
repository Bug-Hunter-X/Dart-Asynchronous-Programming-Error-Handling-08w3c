# Dart Asynchronous Programming Error Handling

This repository demonstrates a common error in Dart asynchronous programming and its solution.

## Bug Description
The `fetchData` function uses `http.get` to fetch data from an API. The `try-catch` block handles exceptions, but it doesn't specify the type of exception. This makes debugging more difficult, as all exceptions are caught in one block.  Specific error handling is missing.

## Solution
The improved `fetchData` function handles the exceptions in a more specific and informative manner, improving error handling and debugging.
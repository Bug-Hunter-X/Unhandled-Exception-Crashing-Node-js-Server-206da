# Unhandled Exception in Node.js Server

This repository demonstrates a common issue in Node.js applications: unhandled exceptions that lead to server crashes. The `server.js` file showcases a server that throws an exception when a specific URL is requested.  However, the exception isn't properly handled, resulting in the server process terminating abruptly.

The `serverSolution.js` file provides a corrected version with improved error handling using a `try...catch` block within the request handler and a more comprehensive `server.on('error', ...)` event listener.

This example highlights the importance of robust error handling in Node.js to prevent unexpected crashes and maintain application stability.
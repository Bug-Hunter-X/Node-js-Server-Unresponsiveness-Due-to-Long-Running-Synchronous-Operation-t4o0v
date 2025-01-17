# Node.js Server Unresponsiveness

This repository demonstrates a common issue in Node.js where a server becomes unresponsive due to a long-running synchronous operation within the request handler.  The provided `server.js` file contains a simple HTTP server that simulates a 5-second delay.  During this delay, the server is unable to process any other requests, effectively hanging.

The `serverSolution.js` file provides a solution using asynchronous operations to prevent this blocking behavior.
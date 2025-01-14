This repository demonstrates a common error in Node.js applications: unhandled promise rejections.  Unhandled promise rejections can lead to unexpected application crashes without any clear error messages. The `bug.js` file shows the problematic code, while `bugSolution.js` provides a solution using the `process.on('unhandledRejection', ...)` event handler.
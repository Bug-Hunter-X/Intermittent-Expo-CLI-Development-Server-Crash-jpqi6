# Expo CLI Intermittent Crash Bug

This repository demonstrates a bug where the Expo CLI development server intermittently crashes without providing useful error messages. The crash is non-deterministic and typically occurs after prolonged use or frequent code changes.  The provided `bug.js` file contains a simplified example that helps reproduce the problem, while `bugSolution.js` shows potential solutions and workarounds. 

## Reproduction Steps

1. Clone this repository.
2. Navigate to the project directory.
3. Run `expo start`. 
4. Observe the behavior of the development server over time.  Frequent changes to `bug.js` may increase the likelihood of encountering the crash.

## Potential Solutions (See `bugSolution.js`)

The solution involves improving the app's resilience and handling of potential errors, and optimizing the developer workflow.

- Thoroughly test the app logic and fix any hidden errors.
- Check for memory leaks or performance bottlenecks.
- Implement proper error handling and logging.
- Optimize large components or data structures.
- Restart the development server as needed.
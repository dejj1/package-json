<h3>1. The Event Loop:</h3>
The event loop is a programming concept used in asynchronous programming(concurrent execution of multiple tasks ), particularly in JavaScript, that allows for non-blocking I/O operations. The event loop runs continuously, waiting for events to occur, and then processes those events one by one.


<h3>2. Six phases of the event loop</h3>
In JavaScript, the event loop consists of six phases, each of which performs a specific task in the processing of events. These phases are as follows:


(i)Timers phase: In this phase, the event loop checks for any timer callbacks that have completed, and adds them to the callback queue.

(ii)I/O phase: In this phase, the event loop checks for any I/O callbacks that have completed, such as network requests or file I/O, and adds them to the callback queue.

(iii)Idle, Prepare phase: In this phase, the event loop performs internal housekeeping tasks and prepares for the next iteration of the loop.

(iv)Poll phase: In this phase, the event loop retrieves new I/O events from the operating system's event queue and adds them to the callback queue. If there are no pending I/O events, the event loop will wait for new events to arrive.

(v)Check phase: In this phase, the event loop executes any callbacks that are on the callback queue, as a result of timer or I/O events.

(vi)Close phase: In this final phase, the event loop executes any 'close' event callbacks, such as when a socket connection is closed.

Once all phases have been completed, the event loop returns to the first phase and begins the process again.

<h3>3. List of some best practices in server-side code development</h3>
(i)Focus on Code Quality - use a formatter like Prettier and a linter like ESLint
(ii)Prefer ES6+ and Async/Await
(iii)Keep Code Small - Modularize your codes and employ Microservice architecture
(iv)Handle Errors.

<h3>4. What is NPM5: How do you initialize a package in npm</h3>
NPM5 (Node Package Manager 5) is a version of the Node.js package manager, which is used to install and manage third-party packages and dependencies for Node.js-based applications.

<h3>5. To initialize a package in NPM</h3>
<li>Open your terminal or command prompt.</li> 
<li>Navigate to the directory where you want to create your package.</li>
<li>Type "npm init" and press Enter.</li>
<li>Follow the prompts to provide the required information about your package.</li>
<li>Once you've provided all the necessary information, review the package.json file that was created.</li>
<li>Save or edit and save package.json file</li>

<h3>6. How to run a script in the package.json</h3>
To run a script defined in the package.json file in a Node.js project, you can use the npm run command followed by the script name.

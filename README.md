# Code Challenges

This repo extends the Companion repo to [The Coding Inteview Bootcamp: Algorithms + Data Structures](https://www.udemy.com/course/coding-interview-bootcamp-algorithms-and-data-structure/) - a Stephen Grider Udemy Course.

The code challenges in this folder are based upon common interview code questions and are based on Javascript ES2015.

The only real difference between this and the source repo is the implementation of the jest testing framework. In this repo, the jest module is local to the repo (not global on the users machine), and is setup to be triggered using the standard 'test' script in package.json, with a watch in place to monitor code changes.

---

## Completing the challenges

Each folder in ./exercises contains a challenge. There are always multiple solutions for a challenge, and engineers should seek to explore as many different solutions as possible, taking note of efficiency, complexity and ease of reading. Remember, simple efficient code will always be a winner, as long as it's easy to understand and maintainable.

Within each folder is a index.js file, which describes the problem and where you'd complete the function to solve the problem. There's also a test.js file which contains the test cases for the problem. Please feel free to

### Tips:

1.  Explore as many different solutions as possible.
1.  Note down which ones meet the goals of 'efficiency', 'easy to read' and simple.
1.  Make use of helper methods where this will make the solution easier to read/maintain.
1.  Copy each problem 'folder' into the /attempts folder, rename if you want and use the attempts folder to get pleny of practice.
1.  Get to know Javascript core array methods, string methods and Math library. [Mozilla's Development Network Javascript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference) is a great resource
1.  Sign up for Stephen Griders excellent course (as shown in the introduction). The benefit of being guided through the solution.
1.  Use the test suite (as shown below) to keep a track of your progress and run multiple tests on your solution.
1.  If you're familiar with testing (and the Jest testing framework), you can expand the tests to add new edge-cases or refine the testing paradigm.

---

## Setting up testing

The Jest test suite has been included for ease of use, along with a simple test (watch) script.

To install the "testing" functionality run either

`yarn install`

or

`npm install`

I find yarn is slightly better for commands as you don't need to use 'run' to execute anything(see below). To use yarn, simply execute `npm i -g yarn`.

---

## Running tests

- Navigate to the folder containing the challeng folders.
- For yarn users: `yarn test ./exercise-folder` where exercise-folder is the name of the problem folder.
- For npm users: `npm test ./exercise-folder` where exercise-folder is the name of the problem folder.
- Outputs will be in the terminal/console along with any console.logs used as part of the solution workflow.

Note that the 'test' script in package.json has been set up to watch for changes in code and re-run the test script. If you want to run single test runs instead, you can run `yarn jest ./exercise-folder` or `npm test ./exercise-folder`

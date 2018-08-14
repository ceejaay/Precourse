# Homework #JSII

## Instructions
---
1. Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old.  Doing this will help you quickly discover any holes in your understanding.  Ask your questions on Slack.
		
	* `for`
  

	* `&&`, `||`, `!`
      A computer can only understand human words if we tell it how to understand humand words. Programmers who created Javascript gave some words a shorthand. Some of these shorthands are for And, or and Not.
      && is the same as And. If you told a computer that you wanted to see if it was day time and it was after noon. You would ask a human: Is it daytime right now? Answer yes. Is it after noon? Answer: No. Then you would not it's not time for lunch.  You would write this in Javascript sort of like this if(daytime === true && afternoon === true) {
        return 'time to eat lunch';
      } else {
        return 'not time for lunch';
      }
  || is javascript's word for 'Or.' In the above example. You would write if(daytime === true || afternoon === true). then you would find out if it was either daytime or afternoon.

  The exclamation point is 'not'. if you ask the computer in JS if(afternoon !== true) If the time was 10:00 am the computer would return Yes, it is NOT afternoon. 

2. From the top level of your `Precourse` folder, run `npm test JSII.test.js` to run the automated tests. You will fill out the functions in `homework.js` to make the tests pass.

For more information about Lambda School's six month CS program visit: https://lambdaschool.com

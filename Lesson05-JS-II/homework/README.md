# Homework #JSII

## Instructions
---
1. Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old.  Doing this will help you quickly discover any holes in your understanding.  Ask your questions on Slack.
		
	* `for` for is a way to go through a lot of informations as fast as a computer can do it. When you type for in to a javascript you have to have three instructions. First you need a way to keep track of how many loops the for thing will do. Second, you need the amount of times the for thing will go. Third, you need to tell the computer to go on to the next loop when it's done with the previous loop. So I will tell a computer to set 'i' as the counter. I'll tell the computer to stop when the i equals 5 or when it's gone throught the loop 5 times. The last thing is I'll tell i to add another reminder that we are at loop one or loop two and so on. the syntax look like this for(var i=0;i<5;i++) {we'll do the thing we want to do 5 times here. Like print hello}
    * for is really powerful becaue you can do a lot of repetataive things in a short time. It's what computers are good at.
  

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

# ETH Remix IDE Cognitive Walkthrough

- Repository: https://github.com/ethereum/remix-project
- Web hosted IDE: https://remix.ethereum.org/

## The IDE on at first glance

Upon arriving at the first page of the IDE as a new user I'm a bit confused as to how I should start actually utilzing the IDE. There is no clear path for where I should placve my Solidity files (.sol extension). The Solidity file is where all the source code for my contract goes, this should be very obvious to a new user but is not.

![](RemxiFirstGlance.PNG)

## Further Inspection

After further inspection I notice that there are Solidity files stored for interactions with the web browser, but this still does not answer the question; where should I be coding my smart contract?

![](Remix1.PNG)  

I've now discovered a suite of prebuilt tests for my contract that has yet to be created, this is a very handy feature to be had.

![](Remix2.PNG)  

After conducting outside research on smart contracts and Solidity on the interent I've learned I should place my new smart contract under the "Artifacts" directory.

![](Remix3.PNG)  

## New Contract

As seen below there is no provided default contract for a new user, no "Hello World" type example. This make it extremely difficult for someone that is new to Solidity and now new to the Remix IDE as well to start developing. One of the biggest questions I'm asking myself is what version of Solidity should I be using? 

![](Remix4.1.PNG)  

I decided to navigate over to https://github.com/ethereum/solidity/releases and noticed version 0.7.5 was the latest stable release, this is the version I went with. Though I don't think a new user should necessarily have to do this kind of work as it makes the workflow clunky for a new user.

![](Remix5.PNG)  

## Contract Code

The goal of this walkthrough is to keep things understandable while I disect the Remix IDE, therefore I decided to create a simple smart contract that will return "Hello World". Below is the code.

![](Remix6.1.PNG)  

## Time to Compile

Because I've written a smart contract and interacted with Solidity before this tutorial it's obvious to me the next step is to compile the smart contract. Overall, the compile button was very easy to find on the left-hand side of the screen and lit up with indicators.

![](Remix7.PNG)  

## Time to Deploy

![](Remix8.PNG)  

## Contract Deployed

![](Remix9.PNG)  

## Output

![](Remix10.PNG)

![](Remix11.PNG)

## Conclusion



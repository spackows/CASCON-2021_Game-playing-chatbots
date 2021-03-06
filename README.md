# CASCON 2021 Workshop

**Build a chatbot that can play an ice cream guessing game using IBM Watson Assistant**

Sarah Packowski - IBM ( spackows@ca.ibm.com )<br/>
Christopher Alfonso - IBM ( Christopher.Alfonso@ibm.com )<br/>
Noam Karakowsky - University of Ottawa ( nkarakow@gmail.com )<br/>
Parth Suthar - IBM - ( Parth.Suthar@ibm.com )

<p>&nbsp;</p>


## About the workshop
In this workshop, participants will use Watson Assistant to create a chatbot that can play an ice cream guessing game:
- Player A - _The ice cream oracle_ - Thinks of a flavor of ice cream
- Player B - _The guesser_ - Asks up to 5 yes-or-no questions and then guesses the flavor

In this workshop, participants will build a chatbot to perform the role of Player A.<sup>\[1]</sup>

<img src="images/ice-cream.png" width="300">

The flavors in the game for this workshop are listed below:

<img src="images/chalkboard.png" width="450">

Butterscotch ripple, Strawberry shortcake, Mint chocolate chip, Cookies & cream, Booberry pie, Banana cream pie, Chocolate, Tiger tail, Heavenly hash, Red velvet cake, Cookie dough, Pistachio, Raspberry ripple, Oreo cookie, Chocolate chip, Neapolitan, Rocky road, Maple walnut, Fudge ripple, Chocolate fudge, Vanilla, Strawberry.

\[1] Optional bonus: Instructions and sample files are provided to build a chatbot that can perform the role of Player B and to have two chatbots play the game together.

<p>&nbsp;</p>


## Set up before the workshop
Perform these steps before starting the hands-on workshop:
1. [Register for a free IBM Cloud account](https://cloud.ibm.com/registration)
2. [Create an instance of IBM Watson Assistant (Free, "Lite" plan)](https://cloud.ibm.com/catalog/services/watson-assistant)

<p>&nbsp;</p>


## Instructions
- [Section A: Create an assistant with a dialog skill](#section-a-create-an-assistant-with-a-dialog-skill)
- [Section B: Define entities for colors, ingredients, and flavor names](#section-b-define-entities-for-colors-ingredients-and-flavor-names)
- [Section C: Use a webhook to access the ice cream knowledge base](#section-c-use-a-webhook-to-access-the-ice-cream-knowledge-base)
- [Section D: Implement game play and deploy](#section-d-implement-game-play-and-deploy)
- [Section E: Bonus fun!](#section-e-bonus-fun)

<p>&nbsp;</p>

*Instructions are under construction*

<p>&nbsp;</p>

## Section A: Create an assistant with a dialog skill
See: [Section A demo video](./videos/sectionA.mp4) (~3 minutes)
- Create a welcome message to begin the game
- Create a fallback message for when the chatbot doesn't understand

Full instructions: [README-SectionA](README-SectionA.md)

<p>&nbsp;</p>


## Section B: Define entities for colors, ingredients, and flavor names
See: [Section B demo video](./videos/sectionB.mp4) (~3.5 minutes)
- Recognize when a user mentions a color
- Recognize when a user mentions an ingredient
- Recognize when a user mentions a flavor name

Full instructions: [README-SectionB](README-SectionB.md)

<p>&nbsp;</p>


## Section C: Use a webhook to access the ice cream knowledge base
See: [Section C demo video](./videos/sectionC.mp4) (~7.5 minutes)
- Look up a random flavor to start the game
- Look up yes-or-no answers

Full instructions: [README-SectionC](README-SectionC.md)

<p>&nbsp;</p>


## Section D: Implement game play and deploy
See: [Section D demo video](./videos/sectionD.mp4) (~6 minutes)
- Count the yes-or-no questions
- Validate the flavor guess and end the game
- Deploy chatbot to a web page

Full instructions: [README-SectionD](README-SectionD.md)

<p>&nbsp;</p>


## Section E: Bonus fun!
See: [Section E demo video](./videos/sectionE.mp4) (~7.5 minutes)
- Game play variations with intents
- Giving users options
- Implement a Player B chatbot
- Chabot vs. chatbot: two chatbots playing the game together

Full instructions: [README-SectionE](README-SectionE.md)

<p>&nbsp;</p>



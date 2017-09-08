---
layout: essay
type: essay
title: Google is your Friend
date: 2017-09-07
labels:
  - Computer Science
---

There is a lot of noise in the world today. Everyone talks and asks questions to everyone else. It is ceaseless, and in the shuffle it can seem daunting trying to make your inquiry stand out amongst the sea of other like inquiries. It may be that you think your question is too basic to be interesting, or that no one will have time to respond. In a world where your questions can so easily be passed by on a forum or glanced over in a comment box, it is important to remember to ask “good” questions; questions that will make respondents want to spend time on your question and ignore the countless “bad” questions also hounding them for attention.

### Good Questions?

So what makes a question “good”? To begin, let’s take a look at a question posed on Stack Overflow. The question in this example is titled “Flip a sprite in canvas”. It should be noted that the author may have wanted to say HTML5 canvas instead of just canvas to remove ambiguity, however, the goal of the question comes across well enough and is understandable to anyone who has the knowledge to adequately answer it. The author explains that he is trying to flip a sprite horizontally in a canvas using the drawImage method without having to flip or rotate the entire canvas (a solution he already tried, which did not function as desired).

From the get go, anyone viewing the question is left feeling that the author fully understands what he is asking, has taken the time to try to find solutions himself, and simply has not had enough experience with canvas yet to intuitively know the solution. Due to the quality of his question and the context in which he poses it, the author gets multiple responses that cover methods of flipping a sprite in canvas and how each method might affect his project. One of the solutions involves flipping the context of the canvas, drawing the image (flipped due to the flipped context), and then resetting the canvas context. While that solution is technologically correct and viable, in another solution, the author is told that flipping the context grossly drops performance, so it may be better just to flip the sprite in an image editor and load in the flipped sprite instead. Since the author posed his question within the context of his project, respondents were able to better address all aspects of his question giving the author more solutions to pick through then he likely would have received otherwise. This question is a prime example of a “good” question, the author seemed informed, the problem was clearly stated, and all writing was civil and formal, and because of it the author received multiple highly relevant replies that solve his problem.

### Bad Questions

Now what constitutes a bad question? Well to start we can take a look at another question posed on Stack Overflow, this one titled “Java String.split on emptry string?”. The title is not too bad sans the spelling error; it fulfills the basic goal of summarizing the subject matter of the question, but not much else. The question itself gives a summary of the project that the author is working on which originated the question, then posts a bit of example code recorded identically below. 

```
  String objects; //Could also be empty
  for(String s : objects.split(";")) doSomething();
```
After the block of code, two questions are posed, “Would the loop even run a single time since the string passed is empty?” and “Any major issues that I would have to take care of here?”. While it is easy to tear into this question for its dropping of particular grammars, the most glaring weakness of it is the basicness of its content. The question is quite easily answered by looking up split in the Java String API, which can be found by searching Java String.split. Typically the API is the first place you should go when you want to know more about how a Java function works, not a forum. What’s more, as one respondent to the question brought up albeit in a less direct and politer manner, the poster could have just tested what happens by setting objects equal to an empty string (“”) or null in the code the author provided himself to find the answer he was looking for. So by posting such an inane question, the author gives the impression he is not willing to take the time to look into his own problem, and invest his own time into solving said problem, but would rather leech off of others to solve the issue. This is not the impression you want to leave on others, even people that you only interact with through a coding forum.

### Getting Heard

Making your voice heard is not always the easiest task, however you can greatly improve your chances by making sure you are always asking good “smart” questions. The way you phrase your question, what title you attach to it, what you include with it, all of these factors affect your chances of being heard. There are many things you can do to improve your odds: ask in a clear and concise way, use courteous language and understand no one is obligated to help you, only solicit relevant parties, among many others. The thing you should go out of your way to avoid ever doing though, is posing a bad question, one that could just as if not more easily be solved by a google search. Posing bad questions just adds to the sea of noise that has to be sifted through to find the “good” questions that warrant answering. Always remember if you are debating whether your question is bad, “Google is your friend” (and it won’t complain).

<hr>
Links to the example questions:
<a href="https://stackoverflow.com/questions/7918803/flip-a-sprite-in-canvas">Flip a sprite in a canvas</a>
, 
<a href="https://stackoverflow.com/questions/46105630/java-string-split-on-emptry-string">Java String.split on emptry string</a>

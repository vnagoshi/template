---
layout: essay
type: essay
title: Google is your Friend
date: 2017-09-07
labels:
  - Computer Science
---


### Bad Questions

So what constitutes a bad question? Well to start we can take a look at another question posed on stackoverflow, this one titled “Java String.split on empty string?”. The title is not too bad; it fulfills the basic goal of summarizing the subject matter of the question, but not much else. The question itself gives a summary of what the author is working on that originated the question, then posts a bit of example code recorded identically below. 

```
  String objects; //Could also be empty
  for(String s : objects.split(";")) doSomething();
```

Then two questions are posed, “Would the loop even run a single time since the string passed is empty?” and “Any major issues that I would have to take care of here?”. While it is easy to tear into this question for its dropping of particular grammars, the most glaring weakness of it is the basicness of its content. The question is quite easily answered by looking up split in the Java String API, which can be easily found by searching Java String.split. What’s more, as one respondent to the question brought up albeit more politely, the poster could have just tested what happens by setting objects equal to an empty string (“”) or null in the code the author provided himself. So by posting such an inane question, one that can be easily filed under STFW, the author gives the impression they are not willing to take the time to look into his or her own problems, and invest his or her own time into solving the problem, but would rather leech off of others to solve their issue.

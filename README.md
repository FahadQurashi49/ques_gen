# Automatic Question Generator
Generates questions of four types:
* noun phrases
* verb phrases
* who asked a quote
* question about quote

This project is made for kids short stories, most test run are on stories from:
(http://www.english-for-students.com/Animal-Stories.html)

## Library Used
* https://spacy.io/
* https://github.com/summanlp/textrank
## Usage: 
```
text = '<Any short story>'
question_generator(text)
```
## Result on story: [Elephant and Friends](http://www.english-for-students.com/Elephant-and-Friends.html)
```
sentence:  One day an elephant wandered into a forest in search of friends.
question:  One day Who wandered into a forest in search of friends.

sentence:  "Will you be my friend?" asked the elephant.
question:  "Will you be my friend?", asked who.

sentence:  "Will you be my friend?" he asked the fox.
question:  "Will you be my friend?",who asked the fox.

sentence:  The next day, the elephant saw all the animals in the forest running for their lives.
question:  The next day , the elephant saw what?

sentence:  The elephant asked them what the matter was.
question:  Who asked them what the matter was.

sentence:  The elephant walked up to the tiger and said, "Please, Mr. Tiger, do not eat up these poor animals." 
question:  The elephant walked up to the tiger and said what?
```
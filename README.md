# Wordle-Solving-Bot-using-AI

## About Wordle

This is a popular online word puzzle game where players try to guess a hidden five-letter word. The game provides feedback on each guess, indicating which letters are correct and in the correct position (highlighted in green), which letters are correct but in the wrong position (highlighted in yellow), and which letters are incorrect. Players typically have six chances to guess the correct word. It's often played competitively to see how quickly one can guess the word with the fewest attempts.

<img src='https://github.com/J4tt1n/Wordle-Solving-Bot-using-AI/assets/90543867/f4c4390e-6c8c-48fa-94d8-36be32a9cf35'>

In this algorithm, I use the possible words as well as the extra words to calculate the probability of each charater with respect to its position in the word.

It advises what word should we play, after that getting the hints from the game about the word, it then finds the probability of each of the word from the dataset and then recommends what the next word in the dataset should be. So, in each iteration, I enter the word that I have entered the information i got from that word. 
<div>2 signifies Green i.e. the position of the letter is correct.</div>
<div>1 singifies Yellow i.e. the letter is in the word but at different position.</div>
<div>0 signifies Grey i.e. the letter is not in the word.</div>
<br>

![Screenshot (390)](https://github.com/J4tt1n/Wordle-Solving-Bot-using-AI/assets/90543867/3a26e9c9-a050-4ea0-881f-50a059a5c9e3)

![Screenshot (391)](https://github.com/J4tt1n/Wordle-Solving-Bot-using-AI/assets/90543867/b291fafb-0f3e-4096-bd55-c7602aff2b70)

<h3>As you may notice, when I chose the first word to be shard, based on the information i got, it advised me that 'three' has the highest probability to be the next word.</h3>

Lets try choosing another word from the dictionary.

![Screenshot (392)](https://github.com/J4tt1n/Wordle-Solving-Bot-using-AI/assets/90543867/d54cb998-892b-4a50-8761-4dc38c2fe30a)

<h3>Each when I take slate as the first, based on the information received, it also adviced me that the most probable word is going to be 'three'.</h3>

Download Link: https://assignmentchef.com/product/solved-lab-11-java-programming
<br>
1. Write a JAVA method that will allow the user to guess a secret word.

The computer randomly will pick a word from a dictionary, display as many asterisks as the word’s length and ask the user to enter a letter that might possibly appear on the word. When the user guesses a letter correctly, the * should be replaced with the correct letter. At the end of each guess, the user’s guess to this point will be presented to the user showing the * and correct letters. The user will then be asked to guess again until entire word is revealed.

Here is a partial sample run of the program: (assuming “programming” is the secret word.)

I’m thinking of a secret word:

***********

Guess a letter in our secret word. e

The letter e doesn’t appear in our secret word:

***********

Guess again. m

The letter m appears in our secret word 2 times:

******mm***

Guess again. p

The letter p appears in our secret word 1 times:

p*****mm***

Once the user has correctly guessed all of the letters in the secret word, the program will tell the user they discovered the secret word. The program should keep up with the number of guesses the user made and output that statistic to the user at the end of the game. Use the following code:

import java.util.Random;

class Lab11 {

static void play() {

Random rnd = new Random();

String dictionary = “Bling Bromance Chillax Crunk Droolworthy Frankenfood Hater Illiterati Infomania Locavore Mankini Muggle Noob Obvs OMG Screenager Textspeak Totes Truthiness Twitterati Unfriend Upcycle Whatevs Whovian Woot”;

String word = dictionary.split(” “)[rnd.nextInt(25)];

//code to allow the user to guess the secret word repeatedly

}




public static void main(String[] args) {

//a loop to allow the user to play the game multiple times

}
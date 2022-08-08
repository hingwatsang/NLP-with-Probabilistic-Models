# NLP-with-Probabilistic-Models

In Course 2 of the Natural Language Processing Specialization, I

a) Create a simple auto-correct algorithm using minimum edit distance and dynamic programming, <br>
b) Apply the Viterbi Algorithm for part-of-speech (POS) tagging, which is vital for computational linguistics, <br>
c) Write a better auto-complete algorithm using an N-gram language model, and  <br>
d) Write my own Word2Vec model that uses a neural network to compute word embeddings using a continuous bag-of-words model. <br>



## Assignment 1: Autocorrect
The first assignment of Course 2 in the Natural Language Processing specialization. This assignment gave me a chance to brush up on my python and probability skills. In doing so, I implemented an auto-correct system that is very effective and useful.

By completing this assignment I learnt how to:

<li>Get a word count given a corpus</li>
<li>Get a word probability in the corpus</li>
<li>Manipulate strings</li>
<li>Filter strings</li>
<li>Implement Minimum edit distance to compare strings and to help find the optimal path for the edits</li>
<li>Understand how dynamic programming works</li>



## Assignment 2: Parts-of-Speech Tagging (POS)
The second assignment of Course 2 in the Natural Language Processing specialization. This assignment developed my skills in part-of-speech (POS) tagging, the process of assigning a part-of-speech tag (Noun, Verb, Adjective...) to each word in an input text. Tagging is difficult because some words can represent more than one part of speech at different times. They are Ambiguous. Let's look at the following example:

<li>The whole team played well. [adverb]</li>
<li>You are doing well for yourself. [adjective]</li>
<li>Well, this assignment took me forever to complete. [interjection]</li>
<li>The well is dry. [noun]</li>
<li>Tears were beginning to well in her eyes. [verb]</li> <br>

Distinguishing the parts-of-speech of a word in a sentence helped me better understand the meaning of a sentence. This would be critically important in search queries. Identifying the proper noun, the organization, the stock symbol, or anything similar would greatly improve everything ranging from speech recognition to search. By completing this assignment, I :

<li>Learn how parts-of-speech tagging works</li>
<li>Compute the transition matrix A in a Hidden Markov Model</li>
<li>Compute the emission matrix B in a Hidden Markov Model</li>
<li>Compute the Viterbi algorithm</li>
<li>Compute the accuracy of your own model</li>


## Assignment 3: Language Models: Auto-Complete
In this assignment, I built an auto-complete system. Auto-complete system is something you may see every day.

When you google something, you often have suggestions to help you complete your search.
When you are writing an email, you get suggestions telling you possible endings to your sentence. <br>

By the end of this assignment, I developed a prototype of such a system using an n-gram language model.


## Assignment 4: Word Embeddings
The fourth programming assignment of Course 2.

In this assignment, I practiced how to compute word embeddings and used them for sentiment analysis.

To implement sentiment analysis, you can go beyond counting the number of positive words and negative words.
You can find a way to represent each word numerically, by a vector.
The vector could then represent syntactic (i.e. parts of speech) and semantic (i.e. meaning) structures.
In this assignment, I explored a classic way of generating word embeddings or representations.

I implemented a famous model called the continuous bag of words (CBOW) model.
By completing this assignment, I:

<li>Train word vectors from scratch.</li>
<li>Learn how to create batches of data.</li>
<li>Understand how backpropagation works.</li>
<li>Plot and visualize your learned word vectors.</li> <br>

Knowing how to train these models gave me a better understanding of word vectors, which are building blocks to many applications in natural language processing.



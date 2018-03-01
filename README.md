# Hearthstone Card Embeddings

## Introduction
Find out embeddings for cards, so we can build a strong model to model to evaluate game state without requiring large high-quality game plays by human experts.

## Background

### Neural Network
One key component for game AI, is the ability to judge if a certain game state is good to the player or not. That is, the ability to *evaluate* the game state.  A neural network is widely-chosen to perform this task.

Basically, the minions on the board plays an important role on such an evalution value. However, for a card game like Hearthstone, the cards holding on hand are also important facts. For control deck, the cards already played out, and the cards left in deck should also be taken into consideration.

### Embeddings

### word2vec

## Methods

### Naive method
Recalling that the ultimate goal of the neural network is to evaluate the game state. That is, to estimate if the player is going to win or loss.

If we have enough **high quality** play statistics, we can just use embeddings for card ids, and train the neural network accordingly. Since we have enough training data, and those training data are all with high quality, the weights for the embedding layer should be able to be trained well.

### Requirements
In this project, the goal is to learn these embeddings from game engine itself. We're allowed to ask game engine to generate the.

# SignPredictor

Sign Predictor is a web app that takes inputed values representing locations on the coaches body to recognize a pattern in their signals to figure out if the runner is going to steal, or not.

## Usage

There are 9 letters that can be encoded to represent different body parts. You click the letters in the same order as the coach gave the sign. You will then tell the program if the runner stole or not. Over time as the dataset develops over the game, it will continue to generate an updadted steal sequence.

> Note: This program will only be able to figure out simple signs that have either no indicator, or 1 set indicator. I am working on making it work with multiple indicators or movinig indicators or other.

## Credit

This progeam is based on Mark Rober's video on stealing baseball signs. I based this program off of his ideas.

## Limitations

As I said before, this program only works with signs that have a singal indicator, or no indicator at all. There is also the possibility that the runner misses the sign which could alter results. If enough data is provided, it will be able to overcome a missed sign, but it may take a little while.

# Markov chain generator
 
In a markov chain, no matter how the process arrived at its present state, the possible future states are fixed. In other words, the probability of transitioning to any particular state is dependent solely on the current state and time elapsed. So if we go from one state to another, the next transition will be determined by the probabilistic analysis of the previous state. Using this on a large corpus of text, the algorithm creates a transition matrix. Then, by choosing a random word, we can set it off and generate as much text as we want. As long as the corpus is big enough, the words generated will be similar to the given text.

In this example, I used a collection of Trumps's speeches and tweets ([this one](https://github.com/ryanmcdermott/trump-speeches)). This can be replaced by any large corpus as long as it has uniformity in its language.
You can get them [here](http://www.nltk.org/nltk_data/)

**Possible modifications** - Adding weights to the probabilities so that it makes more sense

This was inspired by Ben Shaver's project on simulating text.

More on Markov chains (future reference): 
https://www.dartmouth.edu/~chance/teaching_aids/books_articles/probability_book/Chapter11.pdf

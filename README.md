# nlp-language-models

(i) Implement a bigram and a trigram language model for sentences, using Laplace smoothing and add-a smoothing. Assume that each sentence starts with the pseudo-token *start* (or two pseudo-tokens *start1*, *start2* for the trigram model) and ends with the pseudo-token *end*. Train your models on a training subset of a corpus (e.g., a subset of a corpus included in NLTK – see http://www.nltk.org/).

(ii) Estimate the language cross-entropy and perplexity of the two models on a test subset of the corpus, treating the entire test subset as a single sequence of sentences, with *start* (or *start1*, *start2*) at the beginning of each sentence, and *end* at the end of each sentence.

(iii) Develop a context-aware spelling corrector which takes a sentence with errors and returns the most probable initial sentence (the user wanted to write) taking into account the distance of each word written from the original word and the context to have some meaning.

# LLMS

Large language models are machine learning models designed to process and analyze text. They are trained on massive amounts of data, and they learn the patterns in the language, allowing them to generate human-like responses to any query we give them.

Large language models are normally based on very large, deep neural networks. Their numerous applications include chatbots, language translation, and text summarization among many others.

## Embedding 
How can we turn words and sentences into numbers

### Word Embedding

Following are the properties

1. **Similarity**: - Words that are similar should correspond to points that are close by 

2. **Analogy & Word Math** - it captures analogy like what puppy is to dog similarlu calf is to cow and then math is that they age in same way

### Sentence embeddings
word embeddings seem to be pretty useful, but in reality, human language is much more complicate there are sturctures and sentences

How about the sums of scores of all the words?  However, the sentence “I am no good” will also correspond to “No, I am good!"

Therefore, we need better embeddings that take into account the order of the words, the semantics of the language

This is where sentence embeddings come into play  it associates every sentence with a vector full of numbers,

### Similarity Between Text

1. Dot Product - similar movies have high dot product for hihgh similarity

2. cosine distance -  similar movies have high cosine
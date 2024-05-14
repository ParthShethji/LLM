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

How about the sums of scores of all the words? However, the sentence “I am no good” will also correspond to “No, I am good!"

Therefore, we need better embeddings that take into account the order of the words, the semantics of the language

This is where sentence embeddings come into play it associates every sentence with a vector full of numbers,

### Similarity Between Text

1. Dot Product - similar movies have high dot product for hihgh similarity

2. cosine distance - similar movies have high cosine

## Attention Mechanism

### attention

words that have more than one definition, it assigns the same vector to all the definitions What if you want to use this word in different contexts?

One Word, Multiple Meanings

Sentence 1: The bank of the river.
Sentence 2: Money in the bank.

In these two sentences, the computer now knows a little more about the context of the word “bank”, as the word has been split into two distinct ones. One whose definition is closer to “river”, and another one whose definition is closer to “money”. That, in short, is how attention mechanisms work

![alt text](image-2.png)
![alt text](image.png)
![alt text](image-1.png)

But how does it understand thet we must focus on river or money only it like gravity the nearer the word is to our target it gets pulled most nearest word

### Attention Mechanism

instead of using one embedding we create muliple embeddings using linear tranformation of those vertices and the take out the most good embedding

![alt text](<Screenshot (13).png>)
![alt text](<Screenshot (83).png>)
![alt text](<Screenshot (15).png>)
![alt text](<Screenshot (16).png>)
![alt text](<Screenshot (18).png>) 
![alt text](<Screenshot (21).png>) 
![alt text](<Screenshot (22).png>) 
![alt text](<Screenshot (24).png>) 
![alt text](<Screenshot (25).png>) 
![alt text](<Screenshot (30).png>) 
![alt text](<Screenshot (31).png>) 
![alt text](<Screenshot (33).png>) 
![alt text](<Screenshot (35).png>) 
![alt text](<Screenshot (40).png>) 
![alt text](<Screenshot (41).png>) 
![alt text](<Screenshot (42).png>) 
![alt text](<Screenshot (44).png>)

`We take a line from apple to orange then me move apple towards orange for 43 towards orange. Because apple is 43% of orange in our equation`

![alt text](<Screenshot (45).png>) 
![alt text](<Screenshot (46).png>) 
`Queries: Used to find the best embedding`

![alt text](<Screenshot (48).png>)
![alt text](<Screenshot (49).png>) 
![alt text](<Screenshot (51).png>)
`keys and queries matrix multiplication: Used to find the linear transformation. `

![alt text](<Screenshot (52).png>) 
![alt text](<Screenshot (55).png>) 
![alt text](<Screenshot (56).png>) 
![alt text](<Screenshot (57).png>) 
![alt text](<Screenshot (58).png>) 
![alt text](<Screenshot (59).png>) 
![alt text](<Screenshot (60).png>) 
![alt text](<Screenshot (63).png>) 
![alt text](<Screenshot (67).png>) 
![alt text](<Screenshot (68).png>) 
![alt text](<Screenshot (69).png>) 
![alt text](<Screenshot (70).png>) 
![alt text](<Screenshot (71).png>) 
![alt text](<Screenshot (72).png>) 
![alt text](<Screenshot (73).png>) 
![alt text](<Screenshot (74).png>) 
![alt text](<Screenshot (76).png>) 
![alt text](<Screenshot (77).png>) 
![alt text](<Screenshot (78).png>) 
![alt text](<Screenshot (79).png>) 
![alt text](<Screenshot (81).png>) 
![alt text](<Screenshot (82).png>)
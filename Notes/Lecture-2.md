#### \~ASCII is an early standard that assigns numbers to English letters, digits, and common symbols.



#### \~Unicode was created because ASCII couldn't represent characters from all languages or many special symbols.

#### Computers store text as numbers, with each character assigned a unique numeric code.



#### \~Before an LLM can process text, it must first convert the text into numerical representations, starting from these character encodings.







### \~Why ASCII isn't enough for AI?





#### \~ASCII and Unicode assign numbers to characters so computers can store and process text.



#### \~These numbers are only unique IDs and do not contain any meaning.

#### Because AI needs to understand relationships between words, simple character IDs are not enough.



#### \~This is why LLMs use embeddings, where words are represented as vectors that capture semantic similarity.



### 

### \~Introduction to Embeddings



#### An embedding is a vector that represents the meaning of a word.

#### Unlike ASCII or Unicode, embeddings are not just IDs.

#### Similar words have similar vectors.



#### Because embeddings are vectors, operations like the dot product can measure similarity between words.



#### This is one of the key ideas that allows LLMs to understand relationships between words.







### \~Tokenization





#### When we type a sentence the way LLM models understand is by breaking them into smaller parts so that the model can understand the what's being said more clearly. These tokens could be words, Characters or words. In general words are mostly used for best efficiency.


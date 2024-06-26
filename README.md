Llm
Self attention: finding the important word
QKV concept
 I love dosa => dosa is primarily imp that is query Q
Then features of dosa = K
V = very in depth features (vectors)
Eqn of self attention = softmax((QK^T/(Dk)^0.5)*V)
dk=dimensionality of matrix and is an integer
Architecture (of transformer)
6 blocks
1.input embedding or encoding -convert words to numbers
2.position encoding
3.self attention
4.feed forward -gives in depth feature extraction that is
5.normalization
6.output

 First convert to embedding vector that is tokenization
Position encoding 1 pe1 = 
Self attention: 

Q=XWq                K=XWk               V=XWv   [ W subscript v]
X=input value
W= weight matrix


Relu activation function
Feed and self layers are very important
(When fine tuning or creating an llm model will have to create a dataset, evaluate, test etc…
So the foundation of transformers is important in the industry.)



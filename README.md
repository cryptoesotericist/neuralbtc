# neuralbtc
Project for building a neuralnet within the Bitcoin Protocol using Script.

## initial thoughts
1. L = number of layers
2. iN = number of nodes per input layer 
3. oN = number of nodes per output layer

## shifting mindset of transactions to non-monetary concept of input/output biases
1. We will essentially start by porting over more common neuralnet designs
2. Start thinking about approaches to our nodes and programs where a bitcoin address is the program reference, so nodes operating fully independent will need their own address (like smartcontracts)
3. Each node in the neural net will have its feedback bias adjusted by incoming transactions (i/o layer)

### proof of concept
1. Custom bitcoin addresses will act as nodes
2. Can we set n number of address to reflect change in heuristics through the chain
3. Validation: we track the current balance and relationship of each node (address) created through each iteration to see if the bias has adjusted properly

## potential uses
1. Image recognition
2. Content curation

## references
1. https://en.bitcoin.it/wiki/Script Bitcoin Script documents
2. http://aima.cs.berkeley.edu/ Artificial Intelligence: A Modern Approach by Russel/Norvig
3. http://wakerly.org/DDPP/ Digital Design Priciples & Practices by Wakerly

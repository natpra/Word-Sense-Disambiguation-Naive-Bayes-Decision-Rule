# Word-Sense-Disambiguation-Naive-Bayes-Decision-Rule
### Following is a code to check the sense of a disambigous word in a document to return its sense.

The idea of the Bayes classifier which is used in this code for word senses is that it looks at the words around an ambiguous word in a large context window as a whole Document. 

Each content word contributes potentially useful information about which sense of the ambiguous word is likely to be used with it. 

The classifier does no feature selection. Instead it combines the evidence from all features. 

The Bayes decision rule is optimal because it minimizes the probability of error. This is true because for each individual case it chooses the class or sense) with the highest conditional probability and hence the smallest error rate. 

### Decision rule for Naive Bayes

Decide s’ if

```math
 s’ = argmax[log P(Sk) + logP(Vj|Sk)]
```

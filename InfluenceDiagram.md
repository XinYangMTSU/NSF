
## ![#ff00ff](https://placehold.it/15/ff00ff/000000?text=+) `1. Bayesian Belief Networks (BBN)`

* BBN is a `probabilistic graphical model` (PGM)
* `Nodes` are the features
* `Edges/Links` represent relations between features.

### ![#ff00ff](https://placehold.it/15/ff00ff/000000?text=+) Pros
* Can calculate explicit probabilities for hypotheses 
* Prior knowledge can be (incrementally) combined with newer knowledge to better approximate perfect knowledge

### ![#ccff99](https://placehold.it/15/ccff99/000000?text=+) Cons
* Require initial knowledge of many probabilities
* Can become computationally intractable


## ![#66ccff](https://placehold.it/15/66ccff/000000?text=+) `2. Recurrent neural network (RNN)`

A recurrent neural network (RNN) is a class of artificial neural network where connections between nodes form a `directed
graph` along a sequence. This allows it to exhibit temporal dynamic behavior for a `time sequence`.

The idea behind RNNs is to make use of sequential information.

<p align="center">
   Figure 1: A recurrent neural network and the unfolding in time of the computation involved in its forward computation.
</p>

<p align="center">
  <img src="http://www.wildml.com/wp-content/uploads/2015/09/rnn.jpg" alt="hardware"/>
</p>

<p align="center">
Source: Nature
</p>

RNNs are called recurrent because they perform the same task for every element of a sequence, with the output being depended
on the previous computations. 


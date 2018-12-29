## ![#ff5566](https://placehold.it/15/ff5566/000000?text=+) `1. Unconstrained influence diagrams`

In this paper they extend the language of IDs with extra features and call the graphs unconstrained influence
diagrams (UIDs).

They extend the language of influence diagrams to cope with decision scenarios where the order of decisions and observations
is not determined. As the ordering of decisions is dependent on the evidence, a step-strategy of such a scenario is a sequence
of dependent choices of the next action. A strategy is a step-strategy together with selection functions for decision actions.
The structure of a step-strategy can be represented as a DAG with nodes labeled with action variables. They introduce the
concept of GS-DAG: a DAG incorprating an optimal step-strategy for any instantiation.

`Jensen, Finn V., and Marta Vomlelová. "Unconstrained influence diagrams." Proceedings of the Eighteenth conference on Uncertainty in artificial intelligence. Morgan Kaufmann Publishers Inc., 2002.` (I have this paper PDF, I can send to you if
you need it.)

## ![#0066ff](https://placehold.it/15/0066ff/000000?text=+) `2. Multi-agent influence diagrams`

In this paper, they propose a graphical representation for noncooperative games: Multi-agent influence diagrams (MAIDs).
The basic elements in the MAID representation are variables, allowing an explicit representation of dependence, or relevance,
relationships among variables. They define a decision variable D' as strategically relevant to D if, to optimize the decision
rule at D, the decision maker needs to consider the decision rule at D'.

`Koller, Daphne, and Brian Milch. "Multi-agent influence diagrams for representing and solving games." Games and economic behavior 45.1 (2003): 181-221.` (I have this paper PDF, I can send to you if you need it.)

## ![#ff00ff](https://placehold.it/15/ff00ff/000000?text=+) `3. Bayesian Belief Networks (BBN)`

* BBN is a `probabilistic graphical model` (PGM)
* `Nodes` are the features
* `Edges/Links` represent relations between features.

### ![#6600ff](https://placehold.it/15/6600ff/000000?text=+) Pros
* Can calculate explicit probabilities for hypotheses 
* Prior knowledge can be (incrementally) combined with newer knowledge to better approximate perfect knowledge

### ![#ccff99](https://placehold.it/15/ccff99/000000?text=+) Cons
* Require initial knowledge of many probabilities
* Can become computationally intractable

## ![#66ff00](https://placehold.it/15/66ff00/000000?text=+) `4. Neural Networks`

### ![#66ccff](https://placehold.it/15/66ccff/000000?text=+) `4.1 Recurrent neural network (RNN)`

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

RNNs are called `recurrent` because they perform the same task for every element of a sequence, with the output being depended
on the previous computations. 

All RNNs have feedback loops in the recurrent layer. This lets them maintain information in 'memory' over time. But, it can be
difficult to train standard RNNs to solve problems that require learning long-term temporal dependencies. This is because the
gradient of the loss function decays exponentially with time (called the `vanishing/exploding gradient problem`).

RNNs have shown great success in many NLP tasks. The most commonly used type of RNNs are LSTMs

### ![#cc99ff](https://placehold.it/15/cc99ff/000000?text=+) `4.2. Long short-term memory (LSTMs)`

`Long Short Term Memory networks` – usually just called “LSTMs” – are a special kind of RNN, capable of learning long-term
dependencies. LSTM networks are a type of RNN that uses special units in addition to standard units. LSTM units include a
'memory cell' that can maintain information in memory for long periods of time. A set of gates is used to control when
information enters the memory, when it's output, and when it's forgotten. This architecture lets them learn longer-term
dependencies.

### ![#ff00ff](https://placehold.it/15/ff00ff/000000?text=+) Pros
* Neural networks are flexible and can be used for both regression and classification problems. Any data which can be made
numeric can be used in the model, as neural network is a mathematical model with approximation functions
* Neural networks are good to model with nonlinear data with large number of inputs
* Once trained, the predictions are pretty fast.
* Neural networks work best with big data.

### ![#ccff99](https://placehold.it/15/ccff99/000000?text=+) Cons
* Neural networks are black boxes, meaning we cannot know how much each independent variable is influencing the dependent
variables.
* It is computationally very expensive and time consuming to train with traditional CPUs.
* Neural networks depend a lot on training data. This leads to the problem of over-fitting and generalization. The mode relies
more on the training data and may be tuned to the data.








# NEURAL NETWORKS

**Unit 1:** Introduction: Biological Neurons and Synapses, Characteristics of Artificial Neural Networks (ANN); Types of Activation Functions.

**Unit 2:** Perceptrons: Perceptrons representation, Concept of linear separability, Limitations of Perceptrons Single layer and multilayer Perceptrons, Perceptron learning algorithms, Introduction to ANN paradigms, Hopfield net, Hamming net, Grossberg / Carpenter net, Kohonen's net.

**Unit 3:** Basic concept of Learning in ANNs: Supervised learning, backpropagation, Unsupervised learning, self- organization, Counter propagation.

**Unit 4:** Hopfield Networks: Network configuration, Hardware Implementation; Learning, Engorging Applications of ANN's.

_**Reference Books**_

1. L.V. Fausett, Artificial Neural Networks, Pearson Education
2. J.M. Zurada, Introduction to Artificial Neural System, Jaico Publisher
3. P.D. Wasserman, Neural Computing Theory and Practice, Coriolis Group
4. Simon Haykin, Neural Networks and Learning Machines, PHI

## Material

**Project Link:** <https://chatgpt.com/g/g-p-6942d67f2efc81919f4d4abda87a25d5-pinkynn/project>

### UNIT 1: INTRODUCTION TO NEURAL NETWORKS

_**1.1 Biological Neuron Model**_

- Structure of biological neuron (dendrites, soma, axon, synapse)
- Signal transmission mechanism
- Comparison with artificial neuron
- Motivation for ANN
- **Lec 2.1 Motivation from Biological Neurons** : <https://youtu.be/qQmMp8fL82w?si=CZJWn3-Cq5T6bxCM>
- **Lec 2.2 McCulloch Pitts Neuron, Thresholding Logic** : <https://youtu.be/6XhSJbfT1pk?si=Ezj4KqloB3-LUMvj>
- **Lec 2.3 Perceptrons** : <https://youtu.be/XKnBn1XZpQI?si=OajMmvRY5pl-kF2Z>

_**1.2 Artificial Neuron (McCulloch–Pitts Model)**_

- Mathematical model of artificial neuron
- Weighted sum and bias
- Threshold logic unit (TLU)
- Input–output relationship
- **MCP(McCulloch Pitts Neuron Model)** : <https://youtu.be/5PWHcSRn2W4?si=7s03AU5qbSHZt5wY>

_**1.3 Characteristics of Artificial Neural Networks**_

- Non-linearity
- Adaptive learning
- Generalization capability
- Fault tolerance
- Parallelism and distributed processing
- Comparison with conventional computing
- **Characteristics of Artificial Neural Network and Structure of Single Layer Neural Network**: <https://youtu.be/oRZxWHAbIXI?si=lY3xkF8BdFx9V0IN>

_**1.4 Types of Activation Functions**_

- Binary step function
- Linear activation function
- Sigmoid (logistic)
- Tanh
- ReLU and variants
- Mathematical properties and graphs
- Role in learning and convergence
- **What is Activation function in Neural Network ? Types of Activation Function in Neural Network** : <https://www.youtube.com/watch?v=Y9qdKsOHRjA>

- **Artificial Neural Network** : <https://youtube.com/playlist?list=PLxCzCOWd7aiHQ9Qyo70JCTkTxczPnVC6s&si=7l2psXZzFTzwRYhd>

📌 _Exam Focus_: Definitions, diagrams, activation function graphs, small numericals.

_**Links**_

- **ChatGPT:** <https://chatgpt.com/share/6942ddcc-29c8-8012-ba96-cd990d984343>
- **Youtube** :
  - **Deep Learning(CS7015): Lec 2.1 Motivation from Biological Neurons**: <https://youtu.be/qQmMp8fL82w?si=KKbipl2kouj5WDKn>

---

### UNIT 2: PERCEPTRONS & ANN PARADIGMS

_**2.1 Perceptron Model**_

- Single neuron perceptron
- Mathematical representation
- Geometry of decision boundary
- **4.3 Perceptron in ML | Implement AND OR function Training Rule using Perceptron Networks** : <https://www.youtube.com/watch?v=SwZevzz7ru0>

_**2.2 Linear Separability**_

- Concept of linearly separable data
- XOR problem
- Geometric interpretation
- Proof of limitation
- **L92: Linearly Separable Patterns in Context of Linear Separability | AND, OR, XOR Problem** : <https://www.youtube.com/watch?v=sgaGp6ENSa0>
- **Lec 2.7 Linearly Separable Boolean Functions** : <https://youtu.be/AjUgxQNZhck?si=l_rXWsDbdllMlb5Q>

_**2.3 Single-Layer Perceptron**_

- Architecture
- Capabilities and constraints
- Classification examples
- **Lec-48: Understanding Single Layer Perceptron (SLP) with Example** : <https://youtu.be/rvxd13IHx1Y?si=UPkMAaMgdGhfvRmW>

_**2.4 Multi-Layer Perceptron (MLP)**_

- Architecture overview
- Role of hidden layers
- Why multilayer networks solve XOR
- Comparison with single-layer perceptron
- **Lec-49: What is Multilayer Perceptron (MLP)?** : <https://youtu.be/BPOl4_vN3IM?si=hDF-NioZm1in2bo>

_**2.5 Perceptron Learning Algorithm**_

- Learning rule
- Weight update equation
- Convergence theorem (statement)
- Step-by-step numerical example
- **Lec 2.5 Perceptron Learning Algorithm** : <https://youtu.be/VRcixOuG-TU?si=cuBTww3iM4FzpsN5>
- **Lec 2.6 Proof of Convergence of Perceptron Learning Algorithm** : <https://youtu.be/vAOI9kTDVoo?si=iQDBOXe68Qa8fzyA>

_**2.6 ANN Paradigms (Associative & Competitive Networks)**_

- Overview of ANN paradigms
- Supervised vs unsupervised paradigms
- **Network Architecture and Learning Paradigms of ANN** : <https://www.youtube.com/watch?v=AcoRUO3zI4o>

_**2.7 Hopfield Network**_

- Architecture
- Energy function
- Stability concept
- Applications (associative memory)
- **Hopfield Network Algorithm with Solved Example:** <https://youtu.be/ssM6SsdJj8M?si=LKYgZtdlS4nhzPcV>

_**2.8 Hamming Network**_

- Architecture
- Pattern classification principle
- **Hamming Network Solved Example** : <https://www.youtube.com/watch?v=Mlz5-lHl_1A>

_**2.9 Grossberg / Carpenter Network (ART)**_

- Adaptive Resonance Theory (ART)
- Stability–plasticity dilemma

_**2.10 Kohonen Self-Organizing Map (SOM)**_

- Competitive learning
- Neighborhood function
- Feature mapping
- **4.6 Self Organizing Maps (SOM) with Example** : <https://www.youtube.com/watch?v=pE-PRqaUCLM>

📌 _Exam Focus_: XOR proof, learning algorithm numericals, network diagrams.

_**Links**_

- **ChatGPT:** <https://chatgpt.com/share/6942faec-faec-8012-b126-6a9509e75c8d>

---

### UNIT 3: LEARNING MECHANISMS IN ANNs

_**3.1 Learning in Neural Networks**_

- Definition of learning
- Error surface concept
- Cost / loss function

_**3.2 Supervised Learning**_

- Training data and target outputs
- Error correction learning
- Examples: Perceptron, MLP

_**3.3 Backpropagation Algorithm**_

- Forward pass and backward pass
- Gradient descent
- Chain rule derivation
- Weight update equations
- Numerical example (mandatory for exams)
- Vanishing gradient (intro level)

_**3.4 Unsupervised Learning**_

- Concept and motivation
- Clustering vs classification
- Hebbian learning rule

_**3.5 Self-Organization**_

- Competitive learning
- Feature extraction
- Kohonen SOM (connection with Unit 2)

_**3.6 Counter Propagation Network**_

- Architecture (Kohonen + Grossberg layers)
- Learning phases
- Applications

📌 _Exam Focus_: Backprop derivation, numericals, learning rule comparisons.

_**Links**_

- **ChatGPT:** <https://chatgpt.com/share/6942fb08-3994-8012-99fb-21ef5625fcb3>

---

### UNIT 4: HOPFIELD NETWORKS & APPLICATIONS

_**4.1 Hopfield Network Configuration**_

- Fully connected recurrent network
- Symmetric weight matrix
- Binary vs bipolar representation

_**4.2 Energy Function in Hopfield Networks**_

- Lyapunov function
- Proof of convergence to stable state
- Mathematical interpretation

_**4.3 Learning in Hopfield Networks**_

- Hebbian learning
- Weight calculation
- Storage capacity

_**4.4 Hardware Implementation of ANN**_

- Analog vs digital implementation
- VLSI perspective (introductory)
- Neuromorphic concepts (basic)

_**4.5 Emerging Applications of ANNs**_

- Pattern recognition
- Image and speech processing
- Medical diagnosis
- Control systems
- Forecasting and optimization

📌 _Exam Focus_: Energy function proof, weight matrix numericals, applications.

_**Links**_

- **ChatGPT:** <https://chatgpt.com/share/6942fb20-fb08-8012-82eb-62d5ce395853>

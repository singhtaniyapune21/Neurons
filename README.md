# Neurons
Simulating neuron firing, action potentials, and neural network interactions using Python, OOP, data analysis, and visualization.
#  Neuron Wars

A Python-based simulation of neuron communication, signal propagation, and basic neural network behavior.

##  About the Project

**Neuron Wars** is a computational biology project that models how neurons respond to stimuli and communicate with one another.

The project gradually builds from a **single neuron** to a **connected neural network**, demonstrating how excitatory and inhibitory neurons affect signal propagation.

It combines **Bioengineering + Python + Object-Oriented Programming + Data Analysis + Visualization** into one interactive project.

---

##  Objectives

* Model the basic behavior of a neuron.
* Simulate membrane potential and threshold-based firing.
* Create and connect multiple neurons.
* Simulate excitatory and inhibitory neurons.
* Study signal propagation through a neural network.
* Perform experiments with different network configurations.
* Analyze neural activity using statistical methods.
* Visualize and compare network behavior.
* Build an interactive neural network simulation.

---

##  Project Structure

The project is developed progressively through the following stages:

### 1. Single Neuron

Created a `Neuron` class containing:

* Resting potential
* Threshold potential
* Current membrane potential
* Stimulus response
* Firing behavior
* Reset functionality

### 2. Action Potential

Created a simplified action potential visualization showing changes in membrane potential over time.

### 3. Multiple Neurons

Created and managed multiple neuron objects using Python lists and loops.

### 4. Neuron Connections

Implemented connections between neurons and simulated signal transmission from one neuron to another.

### 5. Excitatory & Inhibitory Neurons

Introduced neuron types:

* **Excitatory neurons** increase the connected neuron's potential.
* **Inhibitory neurons** decrease the connected neuron's potential.

### 6. Neural Network Simulation

Created connected networks containing multiple neurons and simulated signal propagation through them.

### 7. Experiments

Performed experiments involving:

* Excitatory vs inhibitory neurons
* Different stimulus strengths
* Different neural network configurations

### 8. Data Analysis

Analyzed membrane potential data using:

* Mean
* Maximum
* Minimum
* Range
* Variance
* Standard deviation
* Correlation

### 9. Visualization

Used Matplotlib to visually compare membrane potentials between different network configurations.

### 10. Interactive Simulation

Created an interactive simulation where the user can choose:

* Number of neurons
* Neuron type
* Signal strength

The program then creates the network, connects the neurons, propagates the signal, and displays the final membrane potentials.

---

##  Technologies Used

* **Python**
* **Object-Oriented Programming**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Google Colab**
* **Git**
* **GitHub**

---

##  Results

The simulation demonstrated that:

* Neurons respond to stimuli according to their threshold.
* Signals can propagate through connected neurons.
* Excitatory neurons increase membrane potential.
* Inhibitory neurons decrease membrane potential.
* Different network configurations produce different membrane potential patterns.
* Statistical analysis can be used to compare neural network behavior.
* Visualization makes differences between network configurations easier to understand.
* The interactive simulation allows users to experiment with different neural networks.

---

##  Example Network

One of the tested configurations was:

```text
N1 → N2 → N3 → N4 → N5
E     E     I     E     I
```

Where:

**E = Excitatory**
**I = Inhibitory**

A signal entering the network propagates through the connected neurons, with each neuron modifying the signal according to its type.

---

##  Concepts Demonstrated

This project applies several programming and bioengineering concepts:

**Programming**

* Classes and objects
* Constructors
* Methods
* Lists
* Loops
* Conditional statements
* Object interaction

**Biology**

* Membrane potential
* Threshold potential
* Action potential
* Excitatory signaling
* Inhibitory signaling
* Neural communication

**Data Science**

* Pandas DataFrames
* Statistical analysis
* Correlation
* Data visualization

---

##  Future Improvements

Possible future extensions include:

* More realistic action potential dynamics
* Synaptic weights
* Refractory periods
* Randomized neural networks
* Larger network simulations
* More advanced neural activity visualizations
* Real-time network animation
* Machine learning integration

---

##  Conclusion

Neuron Wars demonstrates how Python can be used to create a simplified computational model of biological neural communication.

The project combines object-oriented programming, biological concepts, statistical analysis, visualization, and user interaction to build a progressively more complex neural network simulation.

It serves as a foundation for exploring the intersection of **Bioengineering, Programming, Data Science, and Computational Neuroscience**.

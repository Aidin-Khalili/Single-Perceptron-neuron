**Overview**

This repository documents my exploration and experimentation with a single neuron perceptron for binary classification. The project is structured into three main experiments, each aimed at investigating the impact of feature manipulation on the perceptron's ability to classify two distinct classes based on two input features.

**Experiment 1: Basic Perceptron Implementation**

Objective
To establish a baseline by applying a single neuron perceptron for classifying two classes using the raw form of two input features.

Implementation Details
Perceptron Model: A single-layer perceptron with a step activation function.
Features: Two raw features (Feature1, Feature2) without any manipulation.
Learning Approach: Supervised learning with a binary classification goal.
Results & Analysis: Briefly discuss the classification accuracy and any observed limitations.

**Experiment 2: Enhanced Feature Inputs (Polynomial Features)**

Objective
To enhance the model's input space by incorporating polynomial forms of the original features and observe the impact on classification performance.

Implementation Details
Enhanced Features:
Squared terms: Feature1², Feature2²
Cubic terms: Feature1³, Feature2³
Methodology: Adding these polynomial terms as additional inputs to the perceptron to explore non-linear decision boundaries.
Results & Analysis: Compare the classification accuracy and decision boundary complexity with the basic implementation.

**Experiment 3: Feature Interaction and Combination**

Objective
To investigate the effect of feature interaction by creating new feature combinations and their impact on the perceptron's classification capability.

Implementation Details
New Feature Combination: Multiplying the original features (Feature1 * Feature2) to introduce interaction terms.
Approach: Use this new combination as an additional input to examine how feature interaction can influence the decision boundary and classification accuracy.
Results & Analysis: Analysis of how feature interaction alters the perceptron's performance compared to previous experiments.

**Conclusion**

Summarize the key findings from each experiment, noting the progression in model performance with each type of feature manipulation. Reflect on the perceptron's ability to adapt to more complex decision boundaries through feature enhancement and interaction.

**Future Work**
Discuss potential extensions of this project, such as experimenting with different activation functions, scaling to multi-class classification, or implementing multi-layer perceptrons to tackle more complex datasets.

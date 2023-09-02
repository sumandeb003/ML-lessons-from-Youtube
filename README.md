# ML-lessons-from-Youtube

1. The output of a sigmoid function is a probability.
2. **ALL THE WEIGHTS OF A NEURON IN AN NN ARE IN A SINGLE ROW OF A WEIGHT MATRIX. EACH LAYER HAS ITS OWN WEIGHT MATRIX `W`.** SO, THE OPERATION OF AN NN LAYER CAN BE WRITTEN AS: $Wx+b$. $b$ IS THE BIAS VECTOR - EACH NEURON HAS ITS OWN BIAS.
3. **The non-linearity of the activation functions adds up in a multi-layered NN and allows us to model complicated decision boundaries.**
4. Great video for visualizing forward propagation through an NN: https://www.youtube.com/watch?v=UOvPeC8WOt8&ab_channel=vcubingx
    - Needs background on linear transformations via matrices. Check 3Blue1Brown video(s) on linear transformation.
5. https://www.youtube.com/watch?v=8ps_JEW42xs&ab_channel=ritvikmath
    - Softmax: Converts a set of values to corresponding probabilities - $S_i  -> P_i$
    - Softmax activation: $P_i = e^{S_i}/\Sigma e^{S_i}$

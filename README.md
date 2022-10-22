# Neuroscience-Modeling the Behavior of Synapses

**Neuroscience-Modeling-the-Behavior-of-Synapses**
This project models the behavior of synapses in Integrate-and-Fire.

The result of the Excitatory mode:

 ![](https://github.com/Fateme-Azizabadi/NNeuroscience-Modeling-the-Behavior-of-Synapses/blob/main/Images/Excitatory.png)

The result of the Inhibitory mode:

 ![](https://github.com/Fateme-Azizabadi/Neuroscience-Modeling-the-Behavior-of-Synapses/blob/main/Images/Inhibitory.png)

When two neurons are connected to each other in an inhibitory way, the neuron whose initial voltage is -60 mv starts spiking earlier than the other neuron. However, the second neuron tries to stop the first neuron from spiking, so after a while, from where in the inhibitory state, the second term has more power in the equation and can further reduce the value of dv/dt.

 ![](https://github.com/Fateme-Azizabadi/Neuroscience-Modeling-the-Behavior-of-Synapses/blob/main/Images/Eq.png)

Therefore, the second neuron manages to slow down the spiking speed of the first neuron, and eventually, both spike together and are synchronized.
However, when two neurons are excitatory connected. The neuron whose initial voltage is -60 mv starts spiking earlier than the other neuron, but the second neuron also accompanies it. Since the value of E_s=0 mv in excitatory mode, the second term does not have much power in the equation. Moreover, it is like this; first, the first neuron turns on, then the second neuron turns on, and they are never synchronized.


 ![](https://github.com/Fateme-Azizabadi/Neuroscience-Modeling-the-Behavior-of-Synapses/blob/main/Images/Result.png)
 
 

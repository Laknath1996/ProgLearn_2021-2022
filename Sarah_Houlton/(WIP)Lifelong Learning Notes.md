[Lifelong Learning Notes](https://arxiv.org/pdf/2004.12908.pdf)

# Abstract
  * Terms
    * tabula rasa - blank slate
    * omnidirectional transfer learning algorithms 
      * decision forests
      * deep networks
    * omni-voter layer
    
# Introduction
  * Easy to simultaneously learn, hard to sequentially learn
  * Catastrophic forgetting
    * performance on prior tasks drops after training on new tasks
  * Two approaches to lifelong learning
    * fixed resources, reallocate space as new things are learned, compress
    * add resources as new data arrives
    * both can only really transfer data forward
  * Omnidirectional learning
    * Builds on progressive neural networks ~*Maybe look for papers here*~
      * new tasks give additional representative capacity
      * [Progressive Neural Networks paper](https://arxiv.org/pdf/1606.04671.pdf)
      * Quadratic space and time complexity
    * "introduction of representation ensembling"
      * enables omnidirectional transfer via 'omni-voter' layer
    * quasi-linear
    * two complimentary omnidirectional learning algorithms
      * based on decision forests
      * based on deep networks  

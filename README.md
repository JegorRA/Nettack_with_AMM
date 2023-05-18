# Adversarial Attacks on Neural Networks for Graph Data
# Adjency Matrix Modification

Implementation of the Nettack method proposed in the paper:   
**[Adversarial Attacks on Neural Networks for Graph Data](https://arxiv.org/abs/1805.07984)**

by Daniel Zügner, Amir Akbarnejad and Stephan Günnemann.   
Published at SIGKDD'18, August 2018, London, UK

Copyright (C) 2018   
Daniel Zügner   
Technical University of Munich    

Modification proposed by Ryabinin Jegor

[Poster & Presentation Slides](https://www.cs.cit.tum.de/daml/forschung/nettack/)

This implementation is written in Python 3 and uses Tensorflow for the GCN learning.
## Requirements
* `numpy`
* `scipy`
* `scikit-learn`
* `matplotlib`
* `tensorflow`
* `numba`

## Installation
`python setup.py install`

## Run the code
 
 To try our code, you can use the IPython notebook `demo.ipynb`.

## Example output
![Nettack example result](https://raw.githubusercontent.com/danielzuegner/nettack/master/example.png)

## Time experiments results
![Image alt](https://github.com/JegorRA/Nettack_with_AMM/raw/main/time.png)

## References
### Datasets
In the `data` folder we provide the following datasets originally published by   
#### Cora
McCallum, Andrew Kachites, Nigam, Kamal, Rennie, Jason, and Seymore, Kristie.  
*Automating the construction of internet portals with machine learning.*   
Information Retrieval, 3(2):127–163, 2000.

and the graph was extracted by

Bojchevski, Aleksandar, and Stephan Günnemann. *"Deep gaussian embedding of   
attributed graphs: Unsupervised inductive learning via ranking."* ICLR 2018.

#### Citeseer
Sen, Prithviraj, Namata, Galileo, Bilgic, Mustafa, Getoor, Lise, Galligher, Brian, and Eliassi-Rad, Tina.   
*Collective classification in network data.*   
AI magazine, 29(3):93, 2008.
#### PolBlogs
Lada A Adamic and Natalie Glance. 2005. *The political blogosphere and the 2004   
US election: divided they blog.*   
In Proceedings of the 3rd international workshop on Link discovery. 36–43.

### Graph Convolutional Networks
Our implementation of the GCN algorithm is based on the authors' implementation,
available on GitHub [here](https://github.com/tkipf/gcn).

The paper was published as  

Thomas N Kipf and Max Welling. 2017.  
*Semi-supervised classification with graph
convolutional networks.* ICLR (2017).

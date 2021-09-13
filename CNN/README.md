# Convolutional Neural Networks

## 1. From Fully-Connected Layers to Convolutions

Disadvantages of FCL when facing natural image learning problem is too big and not computational efficient. CNN is one creative way accepted by machine learning field to exploit known structure in natural images.

### Invariance
 The object to be detect can occur in anywhere inside the images(spatial invariance). CNN systemize the idea of spatial invariance, to learn useful representations with fewer parameters.
 
Generate a few desiderata to guide the design of neural network architecture effective for computer visions.

1. In the earliest layers, the network should respond similarly to the **same patch**, regardless of where it locates in the image. This is called ***translation invariance***.
2. The earliest layers should focus on local regions, without regard for the contents of the image in distant regions. This is the ***locality*** principle. The whole image level predictions can be made after local representation being aggregated. 

#### Constraining the Problem
##### Translation Invariance
##### Locality
### Convolutions
### Summary

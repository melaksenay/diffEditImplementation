# diffEditImplementation
I implemented the paper "DIFFEDIT: DIFFUSION-BASED SEMANTIC IMAGE EDITING WITH MASK GUIDANCE" from scratch, by first implementing Stable Diffusion from scratch, then implementing the main components of the paper:

1. Computing the editing mask
2. Noising with respect to the input query (encoding) to a given timestep **r**
3. Denoising with respect to the target query


Original Image: horse

![image](https://github.com/user-attachments/assets/f17ab882-da69-4664-9669-51374289258c)

Target Image: zebra
![image](https://github.com/user-attachments/assets/a50bf4d7-6b0c-44e6-abe5-d6464d5e1c69)


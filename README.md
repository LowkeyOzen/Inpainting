# Inpainting 

Reimplementaion of an inpainting method based on [this paper](https://graphics.cs.cmu.edu/projects/scene-completion/). This algorithm performs inpainting by searching across a large database using GIST descriptors to find images resembling the one to inpaint, and then performs Poisson blending between the source and target images. I tried to implement both GIST descriptors and a Poisson blending method.

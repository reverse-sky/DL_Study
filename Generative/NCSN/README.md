# Object
Implementation for toy example in paper that "Generative Modeling by Estimating Gradients of the Data Distribution"

# Summary
+ NCSN_toy_Example.ipynb : Jupyter Notebook for testing implementation

+ Forward process using Multi Gaussian distribution
> we just add Gaussian Noise

<img src="./gif/forward_data.gif" width="500" height="500"  />

-----

+ In this paper, Setting $p_{data}(x) = \frac{1}{5}N([-5,-5],I) +\frac{4}{5}N([5,5],I) $
<img src="./gif/wrong_reverse.gif" width="500" height="500"  />

-----

+ So, two distribution score vector filed represent like this. 
<img src="./gif/vector_filed_two_normal.png" width="500" height="500"  />
The image file means, score function represent mean between two distribution. 

----

<img src="./gif/max_vectorfield.png " width="500" height="500"  />

----

<img src="./gif/Score_network_Langevin.gif" width="500" height="500"  />

-----

<img src="./gif/Langevin Dynamics_Vector_field.png" width="500" height="500"  />

---

<img src="./gif/Annealed_Langevin_Dynamics_SigmaTest.png" width="1000" height="500"  />

----

<img src="./gif/Score_network_annealed_Langevin_sigma_max-2.gif" width="500" height="500"  />

----

<img src="./gif/Annealed_Langebin_Dynamics_4distritubion.gif" width="500" height="500"  /> 

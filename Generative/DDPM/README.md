# Object  
This is the Project for CSE Poster presentation.   
The subject is : Where Do Denoising Diffusion Probabilistic Models Pay Attention Layer-Wise? : An Interpretation's Perspective  
key word: DDPM, Grad CAM, XAI   

# **Reference**   
DDPM Coder is follwed by [learnopencv](https://learnopencv.com/denoising-diffusion-probabilistic-models/)  
Grad-CAM code is follwed by [GRAD_CAM_pytorch](https://github.com/jacobgil/pytorch-grad-cam)  


--------------
file Explanation <a href="./DDPM_CAM/">DDPM_CAM</a>
>`activations_and_gradients.py` : modify Grad_CAM package (DDPM need noise input $t$ )  
`base_cam_ddpm.py`:  modify Grad_CAM package (DDPM need noise input $t$ )  
`grad_cam_ddpm.py`: modify Grad_CAM package (DDPM need noise input $t$) , in this project only use grad-cam  
`image.py`   : utils, for example preprocessing, show_cam(derived by grad_cam_pytorch  
`model_targets.py` : actually almost not use. Only use SemanticSegmentationTarget class for image heatmap visualization  
`svd_on_activations.py` : not use 

----  
Diffusion_model.pth  : DDPM pretrained weight for MNIST Dataset
mnist_unet.py  : DDPM Code block diagram is follws
DDPM_GradCam.ipynb : Jupyter notebook for experiments
Poster_Presentation_version.pptx  : explain project 


![image](https://github.com/reverse-sky/DL_Study/assets/45085563/ec8d247d-863d-470c-9d1f-40041c54c7c5)





# Poster
![image](https://github.com/reverse-sky/DL_Study/assets/45085563/48257953-f2fd-4a3f-85a0-08a1be9e9746)

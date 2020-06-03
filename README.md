# Deformable-FlowNet2 

This is an adaption of the FlowNet2 code by NVIDIA. We adapted the FlowNet2 code to incorporate Deformable Convolutions, and conducted ablation studies.

This project was for the Deep Learning course at Columbia, Spring 2019. My partners were Nicholas Sparks and Jacob Portes.

Please see the Report and Presentation folder for more details.

Update 5/2/2020: Rebuilt cuda files and still seems to work for CUDA10/pytorch1.5. Reverted the submodules to the old version so that the scripts run_DFlowNetS, run_FlowNetS work properly. There are two versions of the DCN module that we used, they are called in submodules.py and submodules_new.py. I reverted to "submodules.py" so that the scripts I made run properly.

# Capstone_Project

# Part 1

Problem Statememt: Implement ControlNetLinks to an external site. or equivalent, that takes edges and converts them into real images. The Condition Block MUST be trained from scratch. 

## Part 1 Structure
```
Capstone_Project:
|   capstone_controlnet.ipynb
|   canny_generator.py
|   README.md
|
+---caption
|   |   blip.py
|   |   config.json
|
+---annotater
|   |   __init__.py

```

# Part 2

Problem Statement: Implement in-painting from Scratch. You can use all the trained models, but the final core logic for in-painting must be implemented from scratch.

## Part 2 Structure
```
Capstone_Porject:
|   capstone_inpainting_1.ipynb
|   capstone_inpainting_2.ipynb
|   car_in_front_of_building.jpg
|   car_mask.png
|   cricket.jpg
|   mask_cricket.png
|   README.md

```

## Explanation 

Model used: [Stable-Diffusion-InPainting](https://huggingface.co/stabilityai/stable-diffusion-2-inpainting)

## capstone_inpainting_1.ipynb (using Diffusion Pipeline)

Test Image used: ![image](https://github.com/harshvs4/Capstone_Project/assets/63489899/9a8e484f-ea17-4c3a-bf9b-7e4f19fb671e)   


Mask Image used: ![image](https://github.com/harshvs4/Capstone_Project/assets/63489899/41f8dca0-2736-4db8-910d-6bac70b8a920)   


Result: ![image](https://github.com/harshvs4/Capstone_Project/assets/63489899/4541f978-4dad-4150-bb71-f6e95081261e)    


## capstone_inpainting_2.ipynb (from scratch)

Test Image used: ![image](https://github.com/harshvs4/Capstone_Project/assets/63489899/bc66d5ed-d87d-4b57-80dd-f90f36999fbe)    


Mask Image used: ![image](https://github.com/harshvs4/Capstone_Project/assets/63489899/2110e092-cca2-4ae5-b9a8-436197154815)   


Result: ![image](https://github.com/harshvs4/Capstone_Project/assets/63489899/74fa3ae0-17c4-4fab-8a70-43b3589ce05a)     


## References

[Achieving Superior Images using ControlNet](https://learnopencv.com/controlnet/)    

[Youtube Link](https://www.youtube.com/results?search_query=Train+Stable+Diffusion+from+scratch+controlnet&sp=EgIYAg%253D%253D)     

[Inpainting with Stable Diffusion](https://getimg.ai/guides/inpainting-with-stable-diffusion)   

[YouTube Link](https://www.youtube.com/watch?time_continue=8&v=XI5kYmfgu14&embeds_referring_euri=https%3A%2F%2Fwww.google.com%2Fsearch%3Fq%3Dimplement%2Bin-painting%2Bfrom%2Bscratch%2B%252B%2Bstable%2Bdiffusion%26rlz%3D1C1RXQR_enIN1023IN1023%26sxsrf%3DAPwXEdd&source_ve_path=Mjg2NjY&feature=emb_logo&ab_channel=NerdyRodent)  


# Lumen-Print-Dataset
## Lumen-Print Dataset

##Gathering Data
---

## First Steps
I decided to continue from where I left off on the previous project and create a LoRA using my lumen print dataset and install it in comfyUI. To do this I used CitvitAI and fed it my dataset. My primary goal for this project was to translate the colors and style of a lumen print image, a flat 2-D surface, onto a 3-D model. To do this, I first created a workflow that allowed me to create a 3-D model from a 2-D image by using the Hunyuan3D 2.0 custion nodes. 

![lumenworkflow-3dgood](https://github.com/user-attachments/assets/b043a591-7e7a-4511-bf4d-7bea3be4d34a)

This section was rather successful, as I was able to create a variety of 3-d models of human, objects, and animals. 

## The Problems

My first problem was that I couldn't find any nodes that support transfering a 2-D image onto a 3-D model. After a while of looking around I decided to use the MV-Adapter node to create take a single image, create multiview image, and run those images through a style adapter that would make them look like lumen prints. After that, I would use the Hunyuan3D 2.0 mutliview to 3-D image to create my new model.

![multi](https://github.com/user-attachments/assets/ab766ced-e3c4-494a-bab6-380a60c18287)

However, when trying to install the nodes on ComfyUI, I got a installation error, so I was unable to use the nodes. But if it was successful, the end results would look similar to these results.


## More Problems

After this, I decided to try to use the Comfy-UI-3D pack instead as it could transform a single image into a multi-view set. However, this pack also decided to have installation errors.

## Hopeful Results

I was hopeing to be able to create models like this in ComfyUI and while I was able to generate 3-D models, I primarily had difficulties with texturing. In the future I will (hopefully) fix the installation issues and be able to properly run either MV-Adapter or Comfy-UI-3D and create a functional workflow.

![image3](https://github.com/user-attachments/assets/e68fd9f4-4c06-4491-a9b6-e8fe4764bfdc)
![image2](https://github.com/user-attachments/assets/4c28ce70-774c-4971-9f72-fdbd22c7986e)
![image](https://github.com/user-attachments/assets/a38d2a41-9fc6-4ecb-ad95-9f1c77c86188)





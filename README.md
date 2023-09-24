# sd-webui-samplers-scheduler

## Introduce
A samplers scheduler which can apply different sampler in diffrent generation steps,  

I hope it will be benefit to achieve a balance between generation speed and image quality.

## Requirement
sd webui Version <= 1.5.2  

## How to use
This repository is a extension for sd webui. Just use it as a sd extension!😉  

Choose the Sampler Seniorious to enable the samplers scheduler.

![](https://github.com/Carzit/sd-webui-samplers-scheduler/blob/main/images/example0.PNG)


This samplers scheduler provides 8 sampler units (Sampler 1-8). 

You can choose what kind of sampler used in each unit(choose `None` to unable), and the inference steps for each unit.  

The image generation process will follow the configurations of these 8 units in sequence. 

**Attention: The total steps should be equal to the sum of the steps in every unit!**


![](https://github.com/Carzit/sd-webui-samplers-scheduler/blob/main/images/example1.PNG)

## Available Samplers
12 kinds of mainstream samplers are available:  

- `Euler`
- `Euler a`
- `Heun`
- `Heun++` (my improved version)
- `LMS`
- `DPM2`
- `DPM2 a`
- `DPM++ 2S a`
- `DPM++ SDE`
- `DPM++ 2M`
- `DPM++ 2M SDE`
- `DPM++ 3M SDE`

You can also choose `Skip` to skip certain steps.


## More
The idea of this extension was inspired by Seniorious, a Carillon composed of different talismans.  

Different talismans correspond in sequence to make Seniorious a powerful weapon, and so do the samplers in the samplers scheduler.  

In the end, many thanks to Chtholly Nota Seniorious, the happiest girl in the world.

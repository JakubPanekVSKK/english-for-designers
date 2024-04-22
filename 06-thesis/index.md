## **ENVIRONMENT DESIGN IN VIDEOGAMES WITH EMPHASIS ON THEIR TYPE**

[VIDEO WITH VOICEOVER](https://youtu.be/rC7yLRJYeRc)

Today I will talk about my thesis on the topic of Environmnet design in videogames with emphasis on their type

The main goals of my thesis are:
1) Who creates videogame environments?
2) What are their tasks and goals?
3) What is the procedure of creating such environments?
4) Which techniques and softwares are being used?
5) What are the differences and core elements of game environments in different types of videogames?

Unfortunately, the last chapter is still work in progress and it is currently not ready yet, so I'm gonna skip that one for today.

**Chapter No.1 - Art departments**

In the majority of big game studios, there mainly three departments, that are contributing in the creation of the game environment.

The first department are Concept artists

Concept artist are working on every videogame project from the very beginning. They are the ones that set all the visual basis for every new videogame.
They work on the theme of the game, its atmosphere and every key location in the environment.

They also have to design a visual solution for every videogame mechanic that is invented by the game designers.
Also their work actually doesnt look like this most of the time.

Mostly it looks like this. Quick sketches that are altered and consulted with the art lead very frequently and thoroughly.
Concept artist have to be really quick and effective in their work. 

They need to be able to come up with loads of different concepts for same things and look at things from many different perspectives.

Next department in the pipeline are Level designers.

Level designers are the ones who design the basis of every game environment. They are doing so by blocking out the environmnet with basic shapes and thoroughly testing it. 
They also decide what's gonna happen in the environment. Where will the enemies come from, where are you gonna hide or where and what will jumpscare you. 

This way they can ensure, that the player will be doing and feeling exactly how they want. 
They even need to make sure that all the wanted game mechanics are being actively used through out the gameplay and that the enviromnet allows and encourages the player to use them in the way they were designed.

The final department are Environment artists

Environment artists take both the visual outputs from Concept artists and tested blockouts from Level designers and create a fuctioning and beatiful environment that is well optimized and runs smoothly on the targeted system.

To do this, they need to break down the enviromnet block out into many different 3D assets, such as trees, rocks, walls or even whole buildings and make these as efficiently as possible.
For example, you may create ten different rocks that can be used in a scene as 60 different rocks. If you create them in a smart way, you can rotate and manipulate them in scene so that every time they look like a different rock while still using six times less resources.
Even buildings are made in this way. They are broken down into modular assets, that can be seamlessly connected into each other. So enviroment artist can create whole cities with just few types of modular sets.

**Chapter No.2 - Production Pipeline**

I decided to describe this part on an environment pipeline of videogame called Deadspace remake created by Electronic Arts.
Their pipeline consists of five phases.

Phase 0 - Initial analysis

Because Deadspace is a remake of old title from 2008, in this phase the team analysed the old game and decided how they can change it and make it better.
In case of completely new videogame project, in this phase the team would gather references, create first concepts and design all the basic mechanics for the game.

Phase 1 - Rough Blockout

In this phase the environment is blocked out with basic shapes and broken down into modular kits. This is also where all the testing begins.

Phase 2 - Base Visuals

In the second phase, the basic visuals and the atmosphere are being set.
This means that the artist decide which color palettes will be used in the different parts of the enviroment and they setup basic lighting of the scenes.

Phase 3 - Materials and Enviromnet population

In this phase, the first PBR materials are being created and applied and the first secondary 3D assets are being added into the scene.

Phase 4 - Narrative elements

Narrative elements are basically a secondary supportive way of telling the story of the game. It is done by projecting the past or upcoming events into the environment with many different elements.
These can be for example aging of the scene and assets inside it, any kind of gore or bloodstains, changes in the lighting of the scene etc.
So in this phase, lots of ther secondary assets are being added into the scene to make it more lived in and beliavable.
Also all the materials get another pass of detail, such as grunge, scratches, stains, dirt etc.

Phase 5 - Final compositing and VFX

In this final phase all of the post visual effects and filters are beign added.
These are for example any kind of lens distortions and lens flares, particle systems or volumetrics.

**Chapter No.3 - Production Techniques**

To make every videogame run smoothly on the targeted system, there are many different techniques to maintain the visual level while making it less demanding of performance.

The first of such techniques is normal baking and use of low poly models.

First we need to look at what is a normal map. Normal map is one of many textures frequently used in PBR materials. It can define how light and shadow is being projected onto a surface of the 3D model.

So in the picture there are three cubes. We can take the first cube and model all the detail into it, so we end up with the second cube. In the end we can take both cubes and bake the details of the second cube into a normal map which we project onto the first cube.
That way we end up with an asset which has much lower polycount but still is really detailed. And that's the third cube.

If we take this into more extreme measures, we can use this technique on basically any kind of complex 3D model. We can significantly reduce the polycount while still maintaining almost all the details.

Another technique is use of LODs - Level of detail

What this technique does is that it decimates the geometry of the 3D mesh and reduces the resolution of the textures based on the distance of the object from the player. 
So the more far you get from the object, the less detailed it becomes. This way, your system is able to efficiently use it's performance and render full quality objects only if you are close enough to actually see the full detail. 
And if this technique is used properly you should not even notice a difference in the quality of such objects.

The last technique is light baking
This technique again kinda tricks the player with a visual bluff. When you're creating a 3D environment you place many different light sources through out the scene. In order to make the system use less of its render power, you can bake the light into the texures of those objects, on which the light is being emitted.
The light is then emitted from emission texture of those objects and there are no actual dynamic lights in the scene. Of course, this technique has to be done properly, because if you mess it up, things can look really weird.

In the last, currently work in progress chapter, I'm gonna take different kinds of videogame types, compare their environments and desribe the core elements of these environments and the main differences between them.

So that's all from me for now.

Thank you for your attention!







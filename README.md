# Project: Pearls

When wearing masks, we lose some of our ability to visually express emotion. Pearls is a World AR effect that lets users add smiles to up to five mask-wearing family members and friends.

## Inspiration
Considering the current epidemic, we wanted to make something positive and fun to improve people's social experiences while maintaining adequate safety. We were inspired by emojis and how they allow users to better communicate and express themselves via text.

## What it does
Pearls is a World AR effect that lets users add smiles to up to five mask-wearing family members and friends.

## How we built it
We used the Spark AR face mask demo as a starting point. Unfortunately, there isn't a block for the position of the mouth, so we used the face finder block and positioned the 2D image from the center. Our 2D images were found on the internet and cropped to our needs using GIMP. Also, we added the UI picker block to allow users to change the texture/2D image. Five face finders where used so that up to five individuals can be in the same picture/video. 

## What we learned
Spark AR is a flexible and well-designed app with great tutorials and community support for building out a variety of AR effects. Blender is a powerful but complicated solution for building 3D models.

## What's next for Pearls
The Pearls team has already created 3D models of teeth and lips to animate within Spark AR to create 3D smiles and is working on perfecting and importing a sufficient armature/rigging system to properly transform our 3d models within Spark AR based on eye movements.

## Challenges we ran into
One hurdle was understanding what the FaceFinder block uses to track a face. Was it possible to find a face with a mask? Would it find a face from a side profile? We found that the algorithm focuses on the eyes through trial and error, and we were able to place a 2D image at a fixed position on the face. We also used Blender for the first time to build a 3D model of lips and teeth to use within Spark AR. Learning how to use the Blender application, build a model, and incorporate sufficient armature consumed a substantial amount of time, and we've been unable to determine how to transfer the armature as created in Blender into Spark AR without issues. When trying to import our Blender creation, the OBJ format excluded the armature and the FBX format simplified the armature by automatically removing joints and limbs.

## Accomplishments that we're proud of:
We believe we have created a simple and effective solution to allow users to express themselves safely in a world with Covid-19.

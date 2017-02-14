# AltspaceVR Programming Project - Graphics Impostor

## Instructions

Finish the implementation of an imposter in an example Unity application, and then build some enhancements to extend it.

## Goals

We use this test to get a sense of your coding style and to how you creatively solve both a concrete problem and an abstract one. When we receive your project, here is what we will be asking ourselves:

- Does your imposter look accurate? Is the perspective correct and does it look similar to the example gif?

- Do your enhancements work well?

- Are the enhancements creative, challenging to implement, and just plain cool?

- Is the code well structured, easy to read and understand, and organized well?

To work on the project:

- Fork and clone the repo.

# Part 1 - Realtime Impostor

An imposter is a type of billboard, intended to replace a mesh that is capable of presenting a different texture based on the angle that it is viewed from. This allows it to be viewed from the side or behind while still looking like a reasonable approximation of the original mesh. 

Here is an example of an impostor in action. The object on the left is an actual mesh, the object on the right is a quad with the impostor texture on it that continuously changes its transformation relative to the player.

![](images/impostor-spin.gif)

It's worth noting that though this is similar to a problem we had to solve at AltspaceVR, this section of the project is designed more to be a self-contained project rather than to be a practical solution to a specific problem. 

Often imposters are created offline. In the interest of simplicity, feel free to implement the rendering of the billboard texture as an operation that happens at runtime, re-rendering the billboard texture as needed

The example project has most everything you need **except** for the logic to drive the impostor rendering and transformation.

Here are the defining features that you should replicate:

- The player is able to walk around both objects at a medium distance (2 meters) and have both the original mesh and the impostor look similar

- The player is able to make small changes to their height above and below the imposter while still maintaining a reasonable appearance (does not have to support view from directly above or below)

- The impostor texture is only updated when needed. A reasonable choice here can be when the angle between the impostor surface and the player has exceded a certian degree of deflection

For this part of the project, please **do not** include 3rd party code. You can reference 3rd party code of course, but any code you write for the impostor should be your own. (We'll be asking you how it works!)

# Part 2 - Enhancements

Now that you have a working cursor, and can point at and select objects, now build some functionality that might be fun in VR that showcases your skills and creativity. This is the open ended part of the project, and is your chance to blow us away! 

Some potential ideas:

- Use the cursor to manipulate objects, and add multiplayer!

- Improve the cursor to be more usable.

- Add some custom shaders, behaviors, or effects to objects to show off your graphics chops.

- Add a control scheme or widgets that let the user do stuff with objects.

- Create some kind of interactive game.

- Anything you want! Got some new Unity technique you want to try? Use this as an excuse! Don’t feel limited by the sample scene, feel free to create a new scene and leverage your cursor code in some novel way.

Feel free to use 3rd party code or assets for this part of the project, keeping in mind our assessment criteria (noted at the top of the README.)

## Deliverable

In your repo, you should clobber this README file with your own describing your project. Any instructions or known issues should be documented in the README as well.

**Please be sure to commit a working build to your repo**, just in case we have trouble getting your project to build.

E-mail us a link to your Github repo to `projects@altvr.com`. Please include your contact information, and if you haven't submitted it to us already, your resume and cover letter. 

We hope you have fun working on the project, and we can't wait to see what you come up with!
    
[The Altspace Team](http://altvr.com/team/)
    
##Acknowledgements

*Assets used in this project are from* [Free Furniture Props](https://www.assetstore.unity3d.com/en/#!/content/8822)



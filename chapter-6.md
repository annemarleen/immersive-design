# Chapter VI. Interaction Design - GUI basics

In this chapter:
* Starters: articles for beginning VR-designers
* What about Tutorials?
* Canvas & Interface
* Affordances & Intuitive Natural Interaction
* VR Usability Heuristics & Gestalt
* Terminology
* Github Playground
* Assignment for this chapter


___

# Getting Started

![cockpit](http://blog.leapmotion.com/wp-content/uploads/2015/07/STSCPanel-1024x679.jpg)

### Starters: articles for beginners

* Matt Sundstrom's article [Immersive Design: learning to let go of the screen](https://www.wired.com/2015/04/how-to-design-for-virtual-reality/#.5tp7296su) provides some background on UI-design for VR. Helpful to get started with VR and Interaction.


* Ishaani Mittal's article ["Designing Virtual Reality Experiences"](https://medium.com/inborn-experience/designing-virtual-reality-experiences-b46d53090ca0) explains some basics that beginning VR-experience designers should keep in mind. *'Even though the User Centered Design process remained the same, the design language which worked in a 2D space, did not necessarily hold true for a VR environment.'*

* Ocuclus employees Kristoffer Brady and Richard Emms's (2015) videotalk ["Navigating new worlds: Designing UI and UX for VR](https://www.youtube.com/watch?v=braV_c4M8oI) is interesting just to get started. It provides some basic information about designing for VR, such as behavioural analysis, 3D-canvas, patterns & menus, Degrees of Freedom, periphery. It's a bit outdated already, but still useful for its basics.

* Ryan Betts' article ["Practical VR: a design cheat sheet"](https://virtualrealitypop.com/practical-vr-ce80427e8e9d) provides an overview of practical implementations for VR interaction design. Handy, and a bit more in-depth than the other articles.

* Mark Billinghurst's slideshare ["Using Interaction Design Methods for Creating AR and VR Interfaces"](https://www.slideshare.net/marknb00/using-interaction-design-methods-for-creating-ar-and-vr-interfaces-80097583 explain the profession of Interaction Design from its core and relates it to VR and AR Interface Design.

* [Designing VR Tools: The Good, The Bad and The Ugly](http://blog.leapmotion.com/designing-vr-tools-good-bad-ugly/)
Jody Medich and Daniel Plemmons talked about some of the discoveries our team has made (and the VR best practices we’ve developed) while building VR experiences with the Oculus Rift and the Leap Motion Controller.

## What about Tutorials? - How to Design a Good Game Tutorial

[![Tutorial](http://img.youtube.com/vi/BCPcn-Q5nKE/0.jpg)](http://www.youtube.com/watch?v=BCPcn-Q5nKE "Tutorial")

"*Simply put, as a designer you have to think about how you’re going to teach the player to play your game as you’re building it. If you don’t do this, if you don’t consider the communication problems that are inherent in every complex decision in your game, you’ll deliver a clunky, front-loaded tutorial at the last minute and it’ll really take away from the players’ experience."* - Extra Credits

* [Watch: How to Design a Good Game Tutorial](http://www.youtube.com/watch?v=BCPcn-Q5nKE "Tutorial")
* [Read transcript: How to Design a Good Game Tutorial](https://schoolofgamedesign.com/project/good-video-game-tutorial/)

Guidelines for designing good game tutorials:
1. Less Text
2. Don't front-load
3. Make the tutorial FUN
4. Reinforce learning through PLAY
5. Listen to your players.
6. Skippable
7. Accessible at all times.

___

# User Experience basics

## Canvas & Interface

![link](https://famousframes.com/data/images/frame_size.gif)

“A decision has to be made about how you want to use the frame because technically, the far right and left side of the frame touch, and represent the space directly behind you,” said [Liden](https://famousframes.com/blog/view/the-virtual-reality-of-storyboards). 

[Golden Proportions Canvas](https://cdn.dribbble.com/users/266011/screenshots/2724399/shot.gif)

## Affordances & Intuitive Natural Interaction

![Teapot](https://s3-eu-west-1.amazonaws.com/demodernsite/amazon/Blog/Touchscreen-Affordance/Affordance_Typen.jpg)

### Building Affordances
The classic example of an [affordance is the handle on a teapot](http://blog.leapmotion.com/vr-interfaces-teapots-common/), which is designed to be easy to hold, and exists to prevent people from scorching their fingers. Conversely, the spout is not designed to appear grabbable. In computer interface design, an indentation around a button is an affordance that indicates that it can be moved independently of its surroundings by pressing. The color, shape, and label of a button advertise its function. Solid affordances are critical in VR interactive design. They ensure that your users understand what they can do, and make it easier for you to anticipate how your demo will be used. The more specific the interaction, the more specific the affordance should appear. In other words, the right affordance can only be used in one way. This effectively “tricks” the user into making the right movements. In turn, this makes the object easier to use, and reduces the chance of error.

### Intuitive Natural Interaction

![link](https://www.wired.com/wp-content/uploads/2015/04/11UaRjr97fGePBtuMFkbqpw-1.png)

To provide intuitive natural interactions, our interfaces must be:
* Learnable
* Understandable
* Habitual

**Mouse Buttons vs. Touch Buttons**

![link](https://www.wired.com/wp-content/uploads/2015/04/1r2F7F9q62O-gU1sw9g6eMA-1.png)

Mouse-activated buttons look small enough to be hit with your mouse, while touchscreen buttons are big enough to be hit with your finger. The size of an object or its constituent parts can suggest what kinds of physical interactions will work with it.

#### [article 2: Designing Physical Interactions for Objects that don't exist](http://blog.leapmotion.com/designing-physical-interactions-for-objects-that-dont-exist/)

#### [article 3: User Interface Type in FPS - non-diegetic, diegetic, adaptive](https://jyx.jyu.fi/bitstream/handle/123456789/56744/URN:NBN:fi:jyu-201801151208.pdf?sequence=1)

## VR Usability Heuristics & Gestalt

Remember that these [Designing for VR: Applying Usability Heuristics to Virtual Reality](https://omobono.com/insights/blog/designing-vr-applying-usability-heuristics-virtual-reality) exist as lenses through which to critique and examine an interaction, not as hard and fast rules.

**Design**
* Aesthetics
* Autonomy
* Colour
* Consistency
* Discoverability
* Efficiency of the User
* Fitt's Law
* Learnability
* Metaphors, Use of
* Readability

**Development**
* Tracking consistency. 
* Ease of detection. 
* Occlusion. 
* Ergonomics. 
* Transitions. 
* Feedback. 

### Gestalt Theory
![Gestalt](https://cdn-images-1.medium.com/max/2000/1*lXzT7FsUZ7KmYFwIdrsZHA.jpeg) 

The Gestalt principles attempt to describe how people perceive visual elements when certain conditions apply. They are built on four key ideas:
* **Emergence**: People tend to identify elements first in their general outlined form.
* **Reification**: People can recognise objects even when there are parts of them missing.
* **Multi-Stability**: People will often interpret ambiguous objects in more than one ways.
* **Invariance**: People can recognise simple objects independently of their rotation, scale and translation.

#### [Gestalt principles](https://medium.muz.li/gestalt-principles-in-ui-design-6b75a41e9965)
* Proximity
* Common Region
* Similarity
* Closure
* Symmetry
* Continuation
* Common Fate 

## Terminology
* [Affordance](http://blog.leapmotion.com/vr-interfaces-teapots-common/): “affordances” refers to the physical characteristics of an object that guide the user in using that object.
* Controller
* [Diegesis](https://en.wikipedia.org/wiki/Diegesis): a term which has been traditionally used to describe a style of narrative storytelling in films and literature.
* [Gaze](https://image.slidesharecdn.com/session7gazepdf-150901000959-lva1-app6891/95/session-7-gaze-2015-2-638.jpg?cb=1441066269): a mode of viewing.
* [Gestalt](https://medium.muz.li/gestalt-principles-in-ui-design-6b75a41e9965)(form, shape in German): a group of visual perception principles developed by German psychologists in 1920s. 
* [Heuristics](https://omobono.com/insights/blog/designing-vr-applying-usability-heuristics-virtual-reality): broad rules of thumb, which are not specific usability guidelines, but does provides directional suggestions.
* [Perceptual Process](http://zhenilo.narod.ru/main/students/Goldstein.pdf): The perceptual process is a sequence
of processes that work together to determine our experience of and reaction to stimuli in the environment.
* Physics Interaction

## Github Playground


# Assignment for this chapter

![Escher](http://www.differenttrainsgallery.com/uploads/2/5/6/6/25666484/m-c-escher-day-night-w_orig.jpg)

**Backward Design**

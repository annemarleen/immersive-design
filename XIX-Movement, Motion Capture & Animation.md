# Chapter - Movement, Motion Capture & Animation

In this chapter:
* Exercise
* Movement Direction for VR
* Motion Capture & Animation (basics)
___

## Exercise character, movement and uncanny valley

1. Show in a visual way how you are using motion and movement in your project.
2. Explain in what way the 'soul' of your characters/avatars/NPCs matches the motions/movements.
3. Is there an uncanny valley issue? Why or why not?
4. What should be improved in order to get a better adjustment between the motion and the character?
5. Present your work and explain the design choices according to the provided resources, which are displayed below.
6. Make sure the information is easy-to-obtain for others.
___

## Movement Direction for VR

![motion](https://media.giphy.com/media/mMJxoSZDvyuSQ/giphy.gif)

### Building Character through Movement

#### [article 1: Movement Direction: Creating Character](https://www.youtube.com/watch?v=1RRc4tq2kpE)

Vanessa Ewan leads the movement direction masterclass, guiding an actor playing Nora from A Doll's House using techniques to explore physicality and enhance character transformation.

### Laban Movement Analysis
Laban Movement Analysis is a theoretical and experiential system for the observation, description, prescription, performance and interpretation of human moment. This can be used in acting and dance to create an emotional response from the audience. Rudolf Laban identified four factors of movement:

* Space: Direct or Indirect
* Weight: Heavy or Light
* Time: Quick or Sustained
* Flow: Bound or Free

Combining these parts creates the Eight Efforts: 
* [Wring](https://www.youtube.com/watch?v=7rvs87Fa3NY)
* [Press](https://www.youtube.com/watch?v=Q3dLyEzhr0s)
* [Flick](https://www.youtube.com/watch?v=BXabAJFNv8s)
* [Dab](https://www.youtube.com/watch?v=dHJD0X-fa9E)
* [Glide](https://www.youtube.com/watch?v=8gv_hZfHels)
* [Float](https://www.youtube.com/watch?v=Axtrk4KniCw)
* [Punch](https://www.youtube.com/watch?v=Y6DJSNpwlts)
* [Slash]

#### Theoretical Imagery

* [Theoretical Imagery: Laban Movement Analysis I](http://www.laban-analyses.org/laban_analysis_reviews/laban_analysis_notation/space_harmony_choreutics/planes/laban_planes_icosahedron.jpg)
* [Theoretical Imagery: Laban Movement Analysis II](https://dryuc24b85zbr.cloudfront.net/tes/resources/6241650/image?width=500&height=500&version=1337895742000)
* [Theoretical Imagery: Laban Movement Analysis III](https://upload.wikimedia.org/wikipedia/commons/2/27/Laban-effort-graph.jpg)
* [Theoretical Imagery: Laban Movement Analysis IV](https://godenicks.files.wordpress.com/2013/11/images-3.jpg)


## Motion Capture & Animation (basics)

![link](http://images.en.koreaportal.com/data/images/full/30518/traditional-methods-of-motion-capture-that-involves-ping-pong-balls-and-multiple-cameras.jpg?w=750)

For in-depth information, contact Freark Broersma: f.j.broersma@hva.nl 

### Hardware

[IKinema project Orion: full body mocap from 6 HTC-Vive Trackers](https://www.youtube.com/watch?v=Khoer5DpQkE)

[Perception Neuron Motion: Capture tutorial](https://www.youtube.com/watch?v=h6nvTYBdiqM)

[Perception Neuron Motion: Building tutorial](https://www.youtube.com/watch?v=AX5y1OhkfWA)

### Software

[Mechanim & Mixamo: in Unity 5: The Basic Basics!](https://www.youtube.com/watch?v=BEIaakl9vJE)

[Mecanim & Mixamo: tutorial Character Animation](https://www.youtube.com/watch?v=256-LXzMt0U)

[Mixamo Import Character Unity](https://www.youtube.com/watch?v=P4PrO8fHZ4E)

[Unity 5: Basic Artificial Intelligence for a Non-Player Character](https://www.youtube.com/watch?v=gXpi1czz5NA)

#### Research on Facial and Body Performance Capture

[Facial Performance Capture using Deep Convolutional Neural Networks video (2017)](https://www.youtube.com/watch?v=VtttfrmfMZw)

[Facial Performance Capture using Deep Convolutional Neural Networks paper (2017)](http://research.nvidia.com/sites/default/files/publications/laine2017sca_paper_0.pdf)

[Convolutional Neutral Networks](http://cs231n.github.io/convolutional-networks/)

#### Animations

Software and plugins:
* Houdini: https://www.sidefx.com/
* Unfold3D for faster UV mapping of 3D models
* Octane render - gpu render
* MDD Deformer for animation
* Maya nCloth

Tips:
* Cheat a more realistic background with depth of field
* 3 point lighting from movies can be used in the scenes
* Refractive index info n and K values for realistic reflection of certain materials:
https://refractiveindex.info/
* Subdivisions off to see better quality in Cinema4D or Houdini
* Import .obj and .mdd files separately instead of .fbx -file to Clo3D for better quality
* Clo3D particle distance
* 5 for super good quality (resolution)
* 20 lower resolution but faster
* Clo3D quats for better quality
* HDR file for lighting with octane
* HDR files are saved at studio shootings to get similar light for example for 3D
objects that are added

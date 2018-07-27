# Chapter Interaction Techniques: Feedback, Feedforward & Force Feedback

In this chapter:
* Exercise
* Interaction Fidelity
* Reference Frames
* Feedback, Feedforward and Force Feedback
* Health-Adverse Symptoms
___

## Exercise reference frames & force-feedback-forward

![Sheldon](https://media.giphy.com/media/xTiQyI0qPIYaMzyyVa/giphy.gif)

1. First watch [SHELDON COOPER & VIRTUAL REALITY](https://www.youtube.com/watch?v=DWpD7G2IcEY)
2. How you defined your reference frames (real/virtual world-torso-hand-head-eye)
3. Show how you work with feedback, feedforward. (single loop - double loop)
4. Do you use Force Feedback? Why? Explain in-depth what you think is the benefit of using or not using force feedback?
5. Present your work and explain the design choices according to the provided resources, which are displayed below.
6. Make sure the information is easy-to-obtain for others. 
___

## I. Interaction Fidelity
It is often assumed that more realism is always desirable in VR, yet this is not fully understood. Realistic interactions are VR interactions that work as closely as possible to the way we interact in the real world. The other end of the interaction fidelity spectrum is non-realistic interactions, that in no way relate to reality. For instance: pushing a button on a non-tracked controller to shoot a laser from the eyes. This interaction has a low fidelity. However, low interaction fidelity is not necessarily a disadvantage as it can increase performance, cause less fatigue and increase enjoyment. In the middle of the spectrum are the magical interactions, where users make natural physical movements, but the technique makes users more powerful by giving them new and enhanced abilities or intelligent guidance. Although not realistic, magical interactions often uses interaction metaphors to help users quickly develop a mental model of how an interaction works.

[How Does Interaction Fidelity Influence User Experience in VR Locomotion?](https://vtechworks.lib.vt.edu/bitstream/handle/10919/74945/Nabiyouni_M_D_2017_support_1.pdf?sequence=2&isAllowed=y)

### Examples of providing feedback, feedforward and force feedback

* Highlighting objects (visually outlining, changing color of objects)
* Audio cues (short intrusive tones or large audio recordings)
* Passive Haptics (static physical objects that can be touched)
* Rumble (vibration of input device)

## II. Reference Frames

![Exocentric](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSPUgmRHAKxJr7vnzeWk74DlXiF82b9eFJkCeju22itr0P3Lc3W)

* *Virtual-World Reference Frame*: matches the layout of the virtual environment and includes geographic directions (eg. North) and global distances (e.g. meters, inches) independent of how the user is oriented, positioned or scaled. 
* *Real-World Reference Frame*: defined by real world physical space and is independent of any user motion (virtual or physical). For example, as a user virtually flies forward the user's physical body is still located in the real-world reference frame.
* *Torso Reference Frame*: useful for interaction because of proprioception and can be useful for steering in the direction the body is facing.
* *Hand Reference Frame*: defined by the position and orientation of the user's hands, and hand-centric judgements occur when holding an object in the hand. Is especially important when using a phone, tablet or VR controller.
* *Head Reference Frame*: is based on the point between the two eyes and a reference direction perpendicular to the forehead. ([Cyclopean eye](http://3.bp.blogspot.com/-0AYbO-t8Tz0/UbPbuksd3aI/AAAAAAAACls/AyPfFWHwD24/s1600/Diane+Collet.Focus.jpg), [Heads-up Display pilots](https://www.youtube.com/watch?v=ypIbmfm7n8A))
* *Eye Reference Frames*: defined by the position of the eye balls.

#### [article 2: Moving in a Box: Improving Spatial Orientation in Virtual Reality using Simulated Reference Frames.](https://www.youtube.com/watch?time_continue=7&v=fmtfRvn-4GU)

[Navigational Search in VR: Do Reference Frames Help?](http://ispace.iat.sfu.ca/project/navi_search_in_vr/)

## III. Feedback, Feedforward and Force Feedback

### Feedback and Feedforward

Feedback focuses on current performance, whereas FeedForward looks ahead to the next assignment. Positive and Negative feedback can be provided. You can provide single loop feedback (learning for the first time and what you learn) and double loop feedback (re-adjust previously learned and how you learn) and even triple loop feedback (reflect on all that's been learned and why you wanted to learn this) Feedforward primes the user in expected futural behaviour, in order to create an efficient learning process. 

#### [article 3: Feedback and feedforward control (short video)](https://www.youtube.com/watch?v=rjSrO3LyHKs)

[Transformational Learning - single vs. double loop](https://www.youtube.com/watch?v=KI0-qESaSJw)

#### [article 4: Investigating Visual Feedforward for Target Expansion Techniques](https://www.youtube.com/watch?v=jV3VkukDM9U)

[Interactive Feedforward for Improving Performance and Maintaining Intrinsic Motivation in VR](https://www.youtube.com/watch?v=jlum9QYfG4Q)

### Force Feedback

#### CLAW

CLAW acts as a multi-purpose controller that contains both the expected functionality of VR controllers (thumb buttons and joysticks, 6DOF control, index finger trigger) as well as enabling a variety of haptic renderings for the most commonly expected hand interactions: grasping objects, touching virtual surfaces and receiving force feedback. But a unique characteristic of the CLAW is its ability to adapt haptic rendering by sensing differences in the user’s grasp and the situational context of the virtual scene.

#### [article 5: Microsoft Shows New Research in Haptics With ‘CLAW’ VR Controller Prototype](https://www.youtube.com/watch?v=8BZ1JnnBwgI)

As a user holds a thumb against the tip of the finger, the device simulates a grasping operation: the closing of the fingers around a virtual object is met with a resistive force, generating a sense that the object lies between the index finger and the thumb. 
A force sensor embedded in the index finger rest and changing the motor’s response profiles enables the sensing of objects of different materials, from full rigid wooden block to an elastic sponge. 
If the user holds the thumb away from a grasp pose, for example on the handle, shaping the palm instead in a pointing gesture, the controller delivers touch sensations. 
Moving the tip of the finger toward a surface of a virtual objects generates a resistance that pushes the finger back and prevents the finger from penetrating the virtual surface. 
Furthermore, a voice coil mounted under the tip of the index finger delivers small vibrations generated by surface texture as the finger slides along a virtual surface. Sensing the force applied by the user can also help to interact with virtual objects. Pushing a slider allows the experienced friction to signal preferable states or pressure can change attributes of a paint brush or pen in a drawing program.

#### Teslasuit

The world’s first fully integrated smart clothing apparel with Haptic Feedback, Motion Capture, Climate Control and Biometric Feedback systems.

[TESLASUIT: ultimate tech in Smart Clothing](https://teslasuit.io/)

## IV. Health-Adverse Symptoms

When designing for Virtual Reality experiences, it is important to learn how to avoid health-adverse symptoms. We will explain some of the most important body systems that need to be taken into account when designing virtual reality systems. Designing for Balance is key to the success of your experience.

When the sense of balance is interrupted, it causes dizziness, disorientation and nausea. Balance is the result of a number of body systems working together: the eyes (visual system), ears (vestibular system) and the body's sense of where it is in space (proprioception) ideally need to be intact. The sense of balance or equilibrioception is one of the physiological senses related to balance. It helps prevent humans and animals from falling over when standing or moving.

#### Easing physical and emotional pain

[Kirsten Lamberts](https://www.youtube.com/watch?v=c6puQL1IQYY) is a psychologist at the Martini Hospital in Groningen. Her team is researching the effects of Virtual Reality in terms easing physical and emotional pain. Human beings only have a limited attention capacity and virtual reality overloads this attention capacity. Therefore, patients forget their pain for a little while. 

## Proprioception & Vestibular Senses

![proprioception](http://learn.genetics.utah.edu/content/senses/proprioception/proprioception.png)

#### [article 6: Designing Virtual Reality - Don't Mess with the Proprioceptive and Vestibular Senses](https://www.youtube.com/watch?v=xTuvspq4UfE)

The balance organs in the inner ear are part of a larger sensory system that helps us know where all of the parts of the body are relative to each other, and the orientation of the body relative to gravity. This sense is called proprioception.

The [proprioception system](http://learn.genetics.utah.edu/content/senses/proprioception/) also takes in information from our eyes, and from receptors in our skin, muscles, and joints that sense stretch, pressure, and movement. The brain processes all of these sensory inputs, giving us a "mind's eye" view of how all of our body parts are positioned and moving through three-dimensional space.

The [vestibular system](https://www.youtube.com/watch?v=1AZnFszUroI) is the sensory system that provides the leading contribution to the sense of balance and spatial orientation for the purpose of coordinating movement with balance. The brain uses information from the vestibular system in the head and from proprioception throughout the body to understand the body's dynamics and kinematics (including its position and acceleration) from moment to moment.

[A Study on Proprioception and Peripheral Vision in 
Synesthesia and Immersion (2017)](http://www.immersence.com/publications/2017/2017-MBoucher.html)

### Equilibrioception

![Dean Potter](https://i2.wp.com/www.dbtechno.com/wp-content/uploads/2015/05/Yosemite.jpg?resize=620%2C349)

Equilibrioception is the ability to keep your balance and sense body movement in terms of acceleration and directional changes. The sense of balance, which is usually barely noticeable in the background of each of our movements, only becomes manifest in its function during intense stimulation (such as VR-experiences) or in the event of illness, which may quite literally turn your world upside down.

___




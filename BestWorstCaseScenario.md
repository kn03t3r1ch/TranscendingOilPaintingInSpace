 ![MainImage](./img/Oil_1.png)


 
 # Transcending Oil Painting In Void
 ___
 - [Project Description](#project-description)
 - [Worst And Best Case Scenario](#worst-and-best-case-scenario)
    - [Best Case Scenario](#best-case-scenario)
    - [Worst Case Scenario](#worst-case-scenario)
- [ToDo's](#toDo's)
- [Prototype](prototype)
  
___

## Project Description
By visiting the installation one should have the opportunaty to be able to experience a painting in an interactive way. The installation processes in an abstract way the transition of a painting - which oddly comes to live - into an higher state. The question of livelyness in paintings is raised. <br/>
Could a piece of fine art, by beeing looked at a thousand times in his life in the museum, inherit a spark of life and could that develope in somewhat of an alive beeing? If yes, what would bring it to life and how would the liveliness manifest itself? Are there possibilities to interact or communicate with it? What could be the language or habitus of such an artpiece and how would it react if it's aware of itself and his counterpart?

The installation aims towards an oversized oil painting which is projected onto a huge, either curved or flat, projektion wall. Entering the installation one will find her- or himself surrounded by this huge, static and abstract oil painting which fills up the entire area of the projection surface. An enjoyable soundscape surrounds the visitor. Approaching closer the image starts to flow and there is a subtle shift into an odd mood noticable in the soundscape. If one steps even closer, the oil painting starts to form itself plastic objects. Moving oneself infront of the image will cause behavior in movement and sound in the oil painting, that can't yet be interpreted as friendly or agressive towards the perceptionist. By completly diminishing the distance between painting and visitor the mood changes into a defensive and aggressive one. This comes close to the moment when people desperatly want to examine whats behind a piece of art or as some even do, go so far as to touch that piece of art. That is the moment when this is too much to handle for the oil painting and it flees like an animal which doesnt want to be touched into another place, a higher dimension or somewhere else where we as the visitor cant reach it. It's transcended and we as visitors are left only with void.
___


## Worst And Best Case Scenario

 
 ### Best Case Scenario

 * the program is optimised so that it runs on steady 60fps in 1920x1080p - restrictions in complexity of displaying the scalarDistanceField Noise
 * the behavior of the oil painting resembles an alive but abstract beeing
   * the movement follows a set of rules that try to make it feel more alive then only random movements
   * the movements develope together with the different stages of exitement
   * the oil painting responds to body gestures 
   * the sound that the oil painting gives of resembles some kind of abstract language
   * the sound is in sync with the positional behavior
   * changes in material apply to emotional states
   * subtle changes in material are interactive

* there are different stages of excitement in the behavior of the oil painting that can be distinguished from each other
  * 4 stages that can be seen as different emotional stages of the oil painting that resemble the transcending into other higher states
    * first stage: the whole surface of the projection screen is filled, looks like an abstract Oil painting / there is a subtle soundscape 
    * second stage: small parts of the oil painting start to flow / the soundscape turns in a more dissonant or weird direction
    * third stage: the oil painting awakes. It forms several kinds of plastic structures and has a behavior that a visitor of the installation can interact with / the painting starts to "talk"
    * fourth stage: the painting is tending to a more agressive and fragile emotion and when a certain threshold is exceeded the painting disappears into the void / agressive and rough sounds but it still should behave like a language, when the painting has entered the void there should only a wide emptyness heard
  * the transition between these four emotional stages is fluent but recognisable

* It is possible to interact with the oil painting with multiple users

 ### Worst Case Scenario

 * frame drops occur
 * the behavior of the oil painting appears only to be random
   * the connection between image and sound is not in sync
   * the sounds the oil painting is giving of doesn't resemble an abstract language
   * no reaction to gestures of the user
   * materialchanges do not support the mood of the painting and appear to be random

 * there are only two emotional stages
   * first and fourth stage as mentioned before
   * the transition between these two stages is rather rough
  
* no option to be able to interact with the painting with multiple users / only one participant or they are seen as one by the oil painting
  <br/>
___

## ToDo's

* optimising the patch so that it runs at 60 fps with all the different subpatches
* implementing kinect
  * researching gestures
  * checking if multiple user input could work
* more then random behavior / liveliness
  * behavior / movement
    * research how liveliness manifests
    * what are parameters that could be useful
    * how to build 
    * research if flocking behavior is suitable 
    * research if optical flow could be useful
  * material
    * material changes according to the mood of the image
    * interactive on a subconsciouse level to underline the momentary mood
  * sounddesign
    * soundscapes
    * language-design
    * different moods in sound
    * getting used to VCV
* Connection between vvvv and VCV
  * parameter research to connect from VCV to vvvv
* research about compute shader inside of vvvv
  * see if average brightness of an image could work 
* build 4 stages
   * resting and calm 
   * starting to flow
   * beeing able to interact
   * defensive and angry
* looking into possibilities for exhibition
___

## Prototype

By clicking this [link](https://www.youtube.com/watch?v=JbdPJjR85UM&t=36s) you can see the first prototype I have developed to research if I wanted to keep working on this project.

___

## Impressions

![MainImage](./img/Oil_2.png)
![MainImage](./img/Oil_3.png)
![MainImage](./img/Oil_4.png)
![MainImage](./img/Oil_5.png)
![MainImage](./img/Oil_6.png)
![MainImage](./img/Oil_7.png)
![MainImage](./img/Oil_8.png)

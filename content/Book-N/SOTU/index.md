---
title: Shape of Our Universe
type: post
date: 2023-05-10 12:00:00-0400
description: my take on a presentation that changed my life.
---


Today I tried to recreate for my chemistry class a presentation that changed my life. At Governor's School last year one of the math teachers gave an optional lectured titled *Shape of the Universe*. Although this wasn't the only math lecture I attended at Governor's School, and I probably wouldn't have said it was my favorite at the time, it is the one that has stuck with me the most. The original *Shape of the Universe* presentation, along with the other math presentations at Governor's School, really changed my perspective on math. I began to view math as a collection of concepts to be understood, rather than a set of problems to be solved. This presentation in particular helped shift my view, as it contained almost no numbers. It made me realize that numbers were just one way to explore mathematical concepts. Numbers are a tool to understand math, not the purpose of math itself. All that being said, this is my textual adaptation of the presentation I gave today:

## What is topology?

Topology is a bit difficult to define with words; the definition given by a quick Google search is "*the study of geometric properties and spatial relations unaffected by the continuous change of shape or size of figures.*". This definition is a bit difficult to understand, so I find it easier to use an image to explain.

 <img alt-text="An example of topologies of several 2D shapes. The top row contains 4 topologically identical shapes. The middle row contains two similar but topologically unequal shapes. The bottom contains two topologically equal shapes" src="SOTU-topology.jpeg">
 

 Caption: Objects are topologically the same if you can stretch, compress, or bend one shape to produce the other. They are not the same if you have to cut, glue, create a hole, or close a hole.ˀ

The top row of images are all topologically the same because they contain no holes. Any one of those could be stretched and misshappen to form any of the others. The shapes in the second row, although they are visually similar, are not topologically the same. One contains a hole, while the other is simply a circle bent into a strange shape. This means they are topologically different, as you could not create the donut shape from the other shape without cutting or glueing faces.
This is important to note because when I refer to the shape of the universe, I am really referring to its topology. Some of the models I'll be showing aren't uniformly sized. This isn't to imply that one part of the universe would be larger than another; we are only concerned with the *connectedness* of the theoretical spaces. This will make more sense after we look at some visuals.

## A Two Dimensional Universe
Before we explore what the shape of a three dimensional universe might look like, it is useful to think about possible shapes of a two dimensional universe. Let's use the analogy of a game of Pacman.
 
<img alt-text="An animation of a pixel-art pacman game on a cylinderical topology." src="SOTU-Cylinder.gif">

The important thing to note here is how Pacman seems to teleport across the screen upon reaching the edge. You could think of this as teleportation through programming magic, but for the sake of this exercise it is better to think of those two locations as physically joined. To physically join these two locations, you must bend the entire screen to form a cylinder.

 <img alt-text="A 3D render of a game of Pacman on the surface of a cylinder" src="/Book-N/assets/img/SOTU-3DCylinder.jpeg">
 Caption: The above image, as well as all the other 3D renderings of the Pacman world, come from Lev Kruglyak's blog,[^1].

This shows that Pacman does not simply teleport across the screen, but is simply moving around the outside of a cylinder. Of course, Pacman has no understanding of moving through a 3rd dimension. Just as you probably can't imagine moving through a fourth spacial dimension, Pacman can't understand that he exists on the surface of a 3D object. 

Although the cylinder is certainly a more interesting shape than a flat plane, it isn't the *most* interesting possible topology of the Pacman universe. It only connects in one direction, leaving a barrier at the top and bottom of the screen. If we connect those two sides, we end up with a space that looks a bit like this:

 <img alt-text="An animation of a pixel-art pacman game on a torus topology." src="/Book-N/assets/img/SOTU-Torus.gif">

This is essentially the same operation as before, just repeated on the other side. In the first example, we created a cylinder by bending the plane of Pacman's world such that one edge connected to its opposite, leaving two open edges on the cylinder. This process can be repeated to connect those two open edges, resulting in a torus:
 
  <img alt-text="A 3D render of a torus with a pacman game on its surface.." src="/Book-N/assets/img/SOTU-3DTorus.jpeg">


One may think that a spherical universe may yield the same results. If I'm being honest, I don't yet fully understand why it *doesn't*, but I can say that for the rest of this post, it makes a lot more sense to think of this as a torus, rather than a sphere.

### Something a little more Complicated

Now that we understand the basic ideas of bending 2D topologies, we're going to try something a little more complex. We're going to imagine Pacman's universe as a Mobius Strip.
A Mobius strip is a simple shape with a lot of interesting properties, but today we're going to look at how the topology of a mobius strip would be perceived by a 2D creature.

<a title="David Benbennick, CC BY-SA 3.0 &lt;http://creativecommons.org/licenses/by-sa/3.0/&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:M%C3%B6bius_strip.jpg"><img width="512" alt="Möbius strip" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/M%C3%B6bius_strip.jpg/512px-M%C3%B6bius_strip.jpg"></a>

You'll notice that the arrows on the strip flip at a certain point. The arrows are oriented the same at all points across the strip when it is folded into a cylinder, but because of the half-twist in the mobius strip, the arrow is mirrored. A Pacman game with this topology would look something like this:

 <img alt-text="An animation of a pixel-art pacman game on a mobius strip topology." src="/Book-N/assets/img/SOTU-Mobius.gif">

You'll notice that each time Pacman goes through one wall of the game, he comes out the other side mirrored. This operation would be impossible with only two dimensional transformations. This is the equivalent of you, a three dimensional creature, travelling around the universe and coming back to find everything a mirror image of what you remember.
 <img alt-text="An animation of a pixel-art pacman spinning in a circle." src="/Book-N/assets/img/SOTU-transform.gif">

## A Step Further

What would happen if we tried to perform the same operation we used to turn the cylinder into a torus to a mobius strip? If you have a strip of paper in front of you, I encourage you to try. Quickly, though, you'll find that it is impossible. The shape this would create is called a Klein bottle, and is impossible to create in just three dimensions. Just as a 3D shape like a cube can be drawn in 2 dimensions if you're okay with a few lines intersecting, a 4 dimensional shape can be sculpted in three dimensions if you're okay with a few surfaces intersecting.

 <a title="Tttrung, CC BY-SA 3.0 &lt;http://creativecommons.org/licenses/by-sa/3.0/&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Klein_bottle.svg"><img width="128" alt="Klein bottle" src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/Klein_bottle.svg/128px-Klein_bottle.svg.png"></a>

 Caption: You'll notice that, as this is on a computer screen, you are actually looking at a four dimensional shape rendered in 3 dimensions drawn on a two dimensional surface. Funky.

So, what would Pacman's universe look like if it had the topology of a Klein bottle? In one direction, it behaves like a cylinder, one side of the screen leads directly to the other, with no twists. The other side, though is a mobius strip, so going that side leads to coming out the other side as a mirror image.

 <img alt-text="An animation of a pixel-art pacman game on a klein bottle topology." src="/Book-N/assets/img/SOTU-Klein.gif">


## A Three Dimensional Universe
Now that we've explored some possible topologies of a 2D universe, it is time to look at possible three dimensional universes. There are *many* possible topologies of a three dimensional universe that we will not explore (as well as many 2D topologies that we did not explore), but I will show the 3D allegories to the torus and Klein bottle 2D topologies we looked at above. Unfortunately, my art skills are not good enough to create a pixel-art 3 dimensional Pacman universe, but I have drawn a few diagrams. 

 <img src="/Book-N/assets/img/SOTU-3DTours-diagram.jpeg">

The above image show the 3D version of our 2D torus topology. This is what our universe would look like if we existed on the volume of a 4D tours. Just as 2D shapes have 1D edges and 3D shapes have 2D surfaces, 4D shapes have 3D volumes around them. This is impossible for a human brain to fully comprehend, but it does explain how the entire volume of our 3D universe could exist on the "edge" of a 4D object. In this example, going in any direction will lead you right back where you came from, with no mirroring. It is possible, though, that we live in a 3D space in which going far enough in one direction would lead you to find a mirrored image of the world you left, this is the 3D equivalent of the surface of a Klein bottle.

 <img src="/Book-N/assets/img/SOTU-3DKlein-diagram.jpeg">

Each figure is holding a sword to make it clear when one is mirrored. Going through any of the side walls leads you to exit through the opposite side, unmirrored, however the "ceiling" and "floor" are mirrored, the red figure is mirrored as it passes through the floor, and reenters the room in the opposite corner of the cube. These two sides are those connected by the equivalent of a mobius strip. Of course, the figure is not actually passing through a floor or reentering through the ceiling; from the perspective of the figure, the room never ends, it is simply connected to itself. 

## Conclusion, futher reading, and some fun resources.
There are many possible topologies, perhaps infinite possible topologies, of our 3D universe. In my presentation, I only explained a few possible topologies because it had to be short, but there are so many I did not explore. I highly recommend playing with a piece of software called *Curved Spaces*[^2]. It is available on iOS, macOS, and Windows. It also runs on Linux with Wine, but Android seems to be entirely unsupported. 

I also read a few pages from the textbook *The Shape of Space*[^3], which was helpful. I didn't dive too deeply into the concepts explored in that book, but it was useful to look at some of the diagrams.

Some other interesting topologies that I would like to explore and better understand later are the real projective plane and half-turn space. I'm mostly leaving this as a reminder to my future self to read about these topics.

[^1]: Lev Kruglyak's amazing blog post [*The Topology of Pacman*](https://levsblog.quora.com/The-Topology-of-Pacman). Kruglyak's blog seems to follow a similar format to Book-N, although with a lot more rigorous content.
[^2]: [Curved Spaces](https://www.geometrygames.org/CurvedSpaces/index.html), the software program I used to explore some of the topology. I *highly* reccommend playing with this for an afternoon, especially if you have an iPhone.
[^3]: *The Shape of Space - 3rd Edition*, Jeffrey R. Weeks, 2020, Chapman & Hall (look at my citation pretending to follow some official format)
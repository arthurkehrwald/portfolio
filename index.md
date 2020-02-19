## Portfolio

---
# 1999: Future Box Pinball
<img src="images/future_box_tags.jpg?raw=true"/>

---
<img src="images/future_box_thumbnail_with_skribbles.jpg?raw=true"/>

### Summary
This pinball machine has a futuristic twist: Using a transparent TV screen, it projects a virtual ball onto a 3D printed playfield, making it look as though it collides with the real objects underneath. The project was started this semester and is still being worked on.

### Hardware Features
* Transparent Screen
* 3D printed playfield
* Plunger with ultrasonic sensor
* Arcade style buttons
* Quick-Draw™ Beer Holder (patent pending)

### Software Features
* Off-Axis Camera Projection ([Off-Axis-What?!](https://en.wikibooks.org/wiki/Cg_Programming/Unity/Projection_for_Virtual_Reality#Off-Axis_vs._On-Axis_Perspective_Projection))
* Face Tracking (matches game perspective with player perspective)
* Fully modular game programming (no interdependent objects)

---
# Tukki and Champ
<img src="images/tukki_and_champ_tags.jpg?raw=true"/>

---
<img src="images/tukki_and_champ_gameplay.gif?raw=true"/>
<img src="images/tukki_and_champ_thumbnails.jpg?raw=true"/>

### Summary
In “Tukki & Champ” a chameleon rides a toucan and they compete for food in an asymmetrical, local 2-player matchup. One player has the keyboard and controls the bird while the other uses the mouse to aim the chameleon's tongue.

---
# Graph Sync
<img src="images/graph_sync_tags.jpg?raw=true"/>

---
<img src="https://i.gyazo.com/cb60ff3ce690659f991cbc6adc06d729.gif"/>
<img src="images/graph_sync_explanation_labeled.jpg?raw=true"/>

### Summary
This is a personal project I used to learn the basics of C++, graph data structures and problem solving algorithms. It works like this: Each puzzle consists of a set of connected buttons, represented by coloured rectangles. Each cross in the table indicates a connection between two buttons. When a button is pressed, all connected buttons (but not the one that was pressed) change colour in the cycle Red->Green->Blue->Red. The goal is to "sync" the graph such that all buttons have the same colour. In case the player can't do it, I've designed and implemented an algorithm that uses a mixture of brute force and analysis to solve any puzzle of this type instantly (except for ridiculously big graphs). As seen above, the game can alternatively be visualized as a graph, but I chose to use a matrix because I wanted to focus on the technical aspects rather than the user interface.

You can read more about the technical implementation of the game and it's auto-solve algorithm in [this document](/pdf/graphpuzzlegame_documentation_arthurkehrwald.pdf).

<!--<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>-->
<!-- Remove above link if you don't want to attibute -->

# Guidelines for field designers in Rescue

This is a guideline document for the RoboCup Junior Rescue League – inspired by various practices popular among the community.
If you feel like contributing, please do so! Fork the project and open a pull request.


## Objective

The main objective for the field designer is to make a fair competition for all teams – and to find the team with the best robot! 
But what is the best robot? What defines a good robot? I would say: in Rescue it is a good robot if it manages the tasks defined by the rules without human intervention. Short: an autonomous robot that is able to handle a lot of difficulties (defined in the rules). 


## What does not define a good robot

I would also say that a good robot is **not** a robot that:

1. handles things apart from the rules, for example inclinations greater than 25 degrees, or gaps longer than 20cm. So it is important for the field designer to not introduce things at the field that are not in accordance with the rules just because they are harder. We should not add things just because they are hard – we need to follow the rules (because all teams used the rules when specifying their robots). 
2. depends on having luck. The field design should not encourage teams to rely on luck (or premapping). All tasks should be solvable with sensors of the robot. 
3. needs a lot of human help. Teams should not use LoP regularely. A run with low score and no human intervention is better – in my opinion. For you as a field designer this means: don't make the field too hard. Better to have it easy so teams can manage it without any LoP at all! This is better than having a field full of different difficulties. 
4. premaps the arenas. The robot should be autonomous. The field design should not require premapping activities from the team, for example place obstacles where it is impossible to detect if it should go right or left around it. In such cases it will be a lottery if the robot will manage it or not.
5. manages just one kind of difficulties. A true rescue robot should manage as well gaps, intersections, ramps and speedbumps, as the rescue of victims. You should be diversified! 


## Some basic rules
<ol>
  <li><strong>Follow the rules!</strong><br>Don't make anything that is not in accordance with the rules. For example gaps longer than 20 cm.<br></li>
  
  <li><strong>Don't make nonsense just because it is fun for you or the audience – even if it is allowed according to the rules!</strong><br>
  Example: placing an obstacle ontop of an intersection. The robot has no chance to know which direction it should turn without pushing the obstacle away and most robots just move around the obstacles (like it was originally intended). <br>
  <li><strong>Design the path in a way that allows the robot to reach the evacuation zone and rescue victims.</strong><br>
  Don't make a path that never reaches the evacuation zone. Don't design the path to cost so much time that the robot does not have any time to rescue victims. Most teams want to show that the robot can rescue victims! 
This also means: don't block the evacuation point with obstacles so it is impossible to rescue any victims.<br></li>

<li><strong>Don't make it too hard! Don't increase the difficulty of the fields too much.</strong><br>
We want teams to be happy and learn from the competition. To make all teams feel that they succeeded with something!<br> 
Often people think it is easy to make really hard and really easy fields – but it is hard to make something in between. The hardest is to do the next to most difficult fields. <br></li>

<li><strong>Use different kind of difficulties</strong><br>
Don't make a field with just speedbumps and debris. Use other things as well, for example black tiles in maze and gaps in line.<br><br></li>

<li><strong>Avoid things that are unclear and not defined in the rules.</strong><br> 
Like tiles with two or more intersections that have entry and exit in the same direction. It will be impossible to judge if the robot goes in between of the different paths since a LoP is defined by looking at the different tiles the robot visits. The same takes effect if the tile includes a gap.<br></li>

<li><strong>Avoid evil things, even if it is allowed in the rules.</strong><br>
Examples:
<ul> 
<li> placing an obstacle in a roundabout or placing a gap just after an obstacle <br></li>
<li> making the obstacles reflective like the victims and placing them in the evacuation zone. <br></li>
<li> placing a wall just in front of a dead-end in line so the robot doesn't have enough space to turn around.  <br></li>
<li> having two lines just adjacant. There is no minimal distance from a line to another line, but a good standard is to use half the width of a robot (10cm) between lines and between lines and walls. This is because the robot may use some zig-zag pattern to find its way back to the line after obstacles and gaps and it is sad if they find the wrong line. <br></li>
<li> constructing obstacles rounded, transparent or soft is not nice since most sensors will give inaccurate reading when the signal is bouncing against the surface of the obstacle.<br></li>

<li><strong>Don't force team do use randomization in their program or to do pre-mapping activities.</strong><br>
For example don't place an obstacle at a tile near the edge of the field if the field is missing walls. Most probably the robots in Line can't detect the edge of the table and therefore they can not know if they should go right or left around the obstacle.<br></li>
</ol>



## Some tips for more advanced challenges: 

1. Different size and forms of the obstacles. The robot needs to follow the edge of the obstacle around until it finds the line again.
2. The maze will be harder if less walls are used. An easy maze consists of a lot of walls, a hard maze is almost empty (with just a few floating walls). 
3. More floating walls in maze. 
4. Use different forms of speedbumps. It is only the height of the speedbump that is specified, not the floor-area. Make speedbumps from particle boards or similar. 
5. Use a lot of turns in line, and right angles or even acute angles. 
6. Speedbumps on ramps – advanced (e.g. for international levels)
7. Combination of difficulties, for example speedbumps, debris and gaps in the same area. Place them on ramps for extra happiness ;)


## Additional notes
1. Obstacles in evacuation room are allowed, but don't give any points. The same applies to speedbumps in the evacuation zone.
2. Points are awarded for each negotiated difficulty. I.e. if two obstacles are located on the same tile the team will earn 20 points. Please note that the points are not awarded until the robot continues to follow the line on the next tile. 


## License

![cc license](http://i.creativecommons.org/l/by/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution 4.0
International license](https://creativecommons.org/licenses/by/4.0/).

## Credits

Fredrik Lofgren / [@FredrikLofgren](https://twitter.com/fredriklofgren) / http://fredriklofgren.se
Jennifer Krieger / mail@jenniferkrieger.de

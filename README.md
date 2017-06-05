# Guidelines for field designers in Rescue

This is a guideline document for the RoboCup Junior Rescue League. Inspired by various practices popular among the community.

If you feel like contributing, please do so! Fork the project and open a pull request.



## Objective

The main objective for the field designer is to make a fair competition for all teams. To find the team with the best robot! 
But what is the best robot? What define a good robot? I would say in Rescue it is a robot that manage the rules without human intervention. An autonomous robot that can handle a lot of difficulties (defined in the rules). 


## What is not a good robot

I would also say that a good robot is **not** a robot that:

1. handles things outside of the rules, for example inclinations greater than 25 degrees, or gaps longer than 20cm. So it is important for the field designer to not introduce things at the field that is not in accordance iwth the rules just because they are harder. We should not add things just because they are hard, we need to follow the rules (because all teams have used the rules when specifying their robots). 
2. have luck. The field design should not encourage teams to use luck (or premapping). All tasks should be able to be solved with sensors of the robot. 
3. need a lot of human help. They should not use LoP regulary. Better with low score and no human intervention in my opinion. For you as field designer this means don't make the field too hard. Better to have it easy so teams can manage it without any LoP at all! It is better than a field full of different difficulties. 
4. Premaps the arenas. The robot should be autonomous. The field design should not require premapping activities from the team, for example place an obstacle where it is impossible to detect if it should go right or left around it. In such cases it will be a lottery if the robot will manage it or not.
5. Just manages one kind of difficulties. A true rescue robots should manage both gaps, intersections, ramps and speedbumps, and to rescue the victims. You should be diversified! 



## Some basic rules
<ol>
  <li><strong>Follow the rules!</strong><br>Don't make anything that is not in accordance with the rules. For example gaps longer than 20 cm.<br><br></li>
  
  <li><strong>Don't make nonsense just because it is fun for you or the audience. Even if it is allowed according to the rules.</strong><br>
  Like placing an obstacle ontop of an intersection. The robot has no chance to know which direction it should turn without pushing the obstacle away and most robot does just move around the obstacles (since it is the original idea with obstacles). <br>
  <br>
  Don't make a path that never reach the evacuation zone. All teams want to show that the robot can rescue victims. 
Or block the evacuation point with obstacles so it is impossible to rescue any victims.<br><br></li>

<li><strong>Don't make it too hard! Don't increase the difficulty of the fields too steep.</strong><br>
We want teams to be happy. To make all teams feel that they succeeded with something!<br> 
Often people think it is easy to make really hard and really easy fields. But it is hard to make something in between. The hardest is to do the next to most difficult fields. <br><br></li>

<li><strong>Use different kind of difficulties</strong><br>
Don't make a field with just speedbumps and debris. Use other things as well, for example black tiles in maze and gaps in line.<br><br></li>

<li><strong>Avoid things that is unclear and not defined in the rules.</strong><br> 
Like tiles with two or more intersections that have entry and exit in the same direction. It will be impossible to judge if the robot goes in between of the different paths since a LoP is defined by looking at the different tiles the robot visits. The same goes if the tile includes a gap.<br><br></li>

<li><strong>Avoid pure evil things, even if it is allowed in the rules.</strong><br>
Like placing an obstacle in a roundabout or placing a gap just after an obstacle. Or making the obstacles reflective as the victims and place them in evacuation zone. <br>
Or placing a wall just in front of a dead-end in line so the robot doesn't have enough space to turn around. <br>
<br>
Make two lines just adjecant. There is no minimal distance from a line to another line, but a good standard is to use half the width of a robot (10cm) between lines and between lines and walls. This is because the robot may use some zig-zag pattern to find its way back to the line after obstacles and gaps and it is sad if they find the wrong line. <br>
<br>
Make obstacles rounded or soft is not nice since most sensors will give inaccurate reading when the signal is bouncing against the surface of the obstacle.<br><br></li>

<li><strong>Don't force team do use randomization in their program. Or to do pre-mapping activities.</strong><br>
For example don't place an obstacle at a tile near the edge of the field if the field is missing walls. Most probably no robots in line can detect the edge of the table and their robot can therefore not know if they should go right or left around the obstacle.<br><br></li>
</ol>



## Some tips for more advanced challenges: 

1. Different size and forms of the obstacles. So the robot need to follow the edge of the obstacle around until it find the line again.
2. The maze will be harder if using less walls. An easy maze consists of a lot of walls, a hard maze is almost empty (with just a few floating walls). 
3. Use different form of speedbumps. It is only the height of the speedbump that is specified, not the floor-area. Make speedbumps from particle boards or similar. 
4. More floating walls in maze. 
5. Use a lot of turns in line, and right angles or even acute angles. 
6. Speedbumps in the ramp is advanced for international levels
7. Combination of difficulties, for example speedbumps, debris and gap in the same area. Place it in the ramp for extra happiness ;)


## Additional notes
1. Obstacles in evacuation room is allowed, but doesn't give any score. 
2. Points are awarded for each negotiated difficulty. I.e. if two obstacles is located in the same tile the team will earn 20p. But the points are awarded when the robot continue to follow the line in the next tile. 


## License

![cc license](http://i.creativecommons.org/l/by/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution 4.0
International license](https://creativecommons.org/licenses/by/4.0/).

## Credits

Fredrik Lofgren / [@FredrikLofgren](https://twitter.com/fredriklofgren) / http://fredriklofgren.se

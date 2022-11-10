It is defined as the smallest number ($n$) of *real-valued*(this word means that the parameter should be continuous) coordinates needed to represent its [[configuration]]. We can calculate [[degree of freedom]]s for various [[mechanism]]. How to determine the degree of freedoms? We can use the method below.

# Calculation of [[degree of freedom]] of a rigid body 
Degree of freedom of a rigid body: 
*degrees of freedom = (sum of freedoms of the points) - (number of independent constraints)*
By expressing it in terms of variables and independent equations:
*degrees of freedom = (number of variables) - (number of independent equations)*
## For [[spatial rigid body]]
*six* degrees of freedom
## For [[planar rigid body]]
*three* degrees of freedom
# Calculation of degree of freedom of a [[Robot]] 
Degree of freedom of a robot is as follow:
*degrees of freedom = (sum of freedoms of the bodies) - (number of independent constraints)*
For robots, they are mainly composed of [[link]]s and [[joint]]s, thus we can determine a method shown below for directly getting degree of freedom of a robot by counting numbers of [[joint]]s and [[link]]s. For [[joint]]s that are used commonly in robots, their constraints on [[degree of freedom]] of [[link]]s can be seen as below:
![[Pasted image 20221023122027.png]]
## [[Grubler's formula]]
This formula is used to calculate the [[degree of freedom]] of a [[mechanism]], it can bee seen in the file [[Grubler's formula]].
==To find the degree of freedom of a robot, we need to first determine the dimension of spaces it is working in. Then, we can try both directly add up degree of freedoms or use Grubler's formula.
Case by case studies:
1.For a robot grasper, we will treat it as having a [[Revolute joint]] with the ground 
2.==
# reference 
“degrees of freedom” ([Lynch 和 Park, 2017, p. 21](zotero://select/library/items/CK6BYIEW)) ([pdf](zotero://open-pdf/library/items/97TQKNC2?page=21&annotation=HAZ5M9TW)) note link: "zotero://note/u/WLDHXQAU/"
---
aliases: [C-space]
---
It is defined as the $n$-dimensional space that contains all possible configurations of the robot. For [[end effector]]s, their configuration space is called [[task space]]. ==The dimension of [[configuration space]] equals to the [[degree of freedom]]==. Despite dimensions, we can also consider the shape of a [[configuration space]]. ==We use the word [[topology]] to express the different shapes of surfaces.== We can determine whether two surfaces are [[topologically equivalent]] or [[topologically distinct]].  Some configuration space can be expressed as the [[Cartesian product]] of two or more spaces of lower dimension. In order to perform calculations on configuration space, ==we need to numerically represent them, how can we achieve them?==
# numerical representation of [[configuration space]] 
The representation of a space involves a choice of reference frame. We can some parameters to represent a space and this is called the [[explicit parametrization]] of a space. In this representation, sometimes singularities (see [[singularity]]) will come into being. We have two ways to deal with them
## 1.
We can use more than one [[coordinate chart]] on the space, where each coordinate chart is an [[explicit parametrization]] covering only a portion of the space. These charts will overlap with each other and cover the entire space. The charts will form an [[atlas]] of the space.
### advantages
1. representation always use the minimum number of numbers.
### disadvantages
1. extra bookkeeping required to switch representations between coordinate charts.  
## 2. use [[implicit representation]](used in the book)


# reference 
“configuration space” ([Lynch 和 Park, 2017, p. 21](zotero://select/library/items/CK6BYIEW)) ([pdf](zotero://open-pdf/library/items/97TQKNC2?page=21&annotation=ZD7MRG4J)) note link: "zotero://note/u/XUC8IUVV/"
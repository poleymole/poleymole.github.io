---
title: Back to Turtle
layout: post
author: joel.chiappetti
permalink: /back-to-turtle/
source-id: 1eT60IroPjitSGCypScuT-sP9IIlaBL0daVxxbsPOIN4
published: true
---
Today we went back to python(with turtle) and I made a 3D T. You can see how much coding there is in just one letter. There is probably a cleverer way of doing it but this way seems to work even if it is slightly longer. Notice I defined a function instead of just putting it straight into the code. This is because if I end up doing more letters then I can just call the functions instead of writing out the code over and over again.

*import turtle*

*def letter_T(Top, Top_Sides, Undersides, Sides, Bottom, Lines):*

*  turtle.forward(Top)*

*  turtle.right(90)*

*  turtle.forward(Top_Sides)*

*  turtle.right(90)*

*  turtle.forward(Undersides)*

*  turtle.left(90)*

*  turtle.forward(Sides)*

*  turtle.right(90)*

*  turtle.forward(Bottom)*

*  turtle.right(90)*

*  turtle.forward(Sides)*

*  turtle.left(90)*

*  turtle.forward(Undersides)*

*  turtle.right(90)*

*  turtle.forward(Top_Sides)*

*  turtle.right(45)*

*  turtle.forward(Lines)*

*  turtle.right(45)*

*  turtle.forward(Top)*

*  turtle.right(90)*

*  turtle.forward(Top_Sides)*

*  turtle.right(90)*

*  turtle.forward(Undersides)*

*  turtle.left(90)*

*  turtle.forward(Sides)*

*  turtle.right(90)*

*  turtle.forward(Bottom)*

*  turtle.right(90)*

*  turtle.forward(Sides)*

*  turtle.left(90)*

*  turtle.forward(Undersides)*

*  turtle.right(90)*

*  turtle.forward(Top_Sides)*

*  turtle.end_fill() *

*  turtle.right(90)*

*  turtle.forward(Top)*

*  turtle.right(135)*

*  turtle.forward(Lines)*

*  turtle.right(180)*

*  turtle.forward(Lines)*

*  turtle.right(135)*

*  turtle.forward(Top_Sides)*

*  turtle.right(45)*

*  turtle.forward(Lines)*

*  turtle.right(45)*

*  turtle.forward(Undersides)*

*  turtle.right(135)*

*  turtle.forward(Lines)*

*  turtle.right(180)*

*  turtle.forward(Lines)*

*  turtle.left(45)*

*  turtle.forward(Sides)*

*  turtle.left(135)*

*  turtle.forward(Lines)*

*  turtle.left(135)*

*  turtle.forward(Bottom)*

*  turtle.left(45)*

*  turtle.forward(Lines)*

*  turtle.right(135)*

*  turtle.forward(Sides)*

*  turtle.right(45)*

*  turtle.forward(Lines)*

*  turtle.left(135)*

*  turtle.forward(Undersides)*

*  turtle.left(45)*

*  turtle.forward(Lines)*

*  turtle.right(135)*

*  turtle.forward(Top_Sides)*

*  turtle.end_fill()*

*letter_T(200, 50, 70, 150, 60, 40)*


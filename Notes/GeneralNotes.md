**Possible weights**
```
One         100		3.7/3.5 pt		
Two         200		5.5%		
Three       300		13%		
Four        400		22.5%	
Five        500		34%		

ExtraLight  100		47.5%	
Light       200		63%
Book        300		80.5%
Regular     400		74/70 70/66 pt		
Medium      500		20%
SemiBold    600		40%
Bold        700		60%
Ekstrabold  800		80%
BLack       900		148/140 pt
```

**Missing glyphs**
* Some small greek ones (currently a 
* Some fractions

**Don't use build function on these**
* L caron
* l caron
* l dot
* only an the letter glyphs - e.g. not accents, space characters etc.

**Creating the _circle_**
```
965 circle +100 -40
8 circle 430*364 -> 390*384
```
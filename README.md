unit_showbuild
==============

SpringRTS widget for Balanced Annihilation game

todo:<br/>
(review from Bluestone)<br/>
this widget is insanely inefficient<br/>
-there is no need to remake each line in each outline for each unit in every drawframe (use nested gllists)<br/>
-there is no need to loop over every item in every unit queue in every gameframe<br/>
-there should not be loops inside DRAWXXX callins, especially not massive ones...<br/> 

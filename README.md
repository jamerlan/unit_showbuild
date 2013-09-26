unit_showbuild
==============

SpringRTS widget for Balanced Annihilation game

todo:
(review from Bluestone)
this widget is insanely inefficient
-there is no need to remake each line in each outline for each unit in every drawframe (use nested gllists)
-there is no need to loop over every item in every unit queue in every gameframe
-there should not be loops inside DRAWXXX callins, especially not massive ones... 

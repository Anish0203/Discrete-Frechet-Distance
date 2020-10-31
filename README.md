# Discrete-Fréchet-Distance

# What is Fréchet Distance?

 The Fréchet distance is a measure of similarity between curves that takes into account the location and ordering of the points along the curves. It is named after Maurice Fréchet.
 The Fréchet distance can be illustrated as follows : suppose a man is walking his dog and that he is constrained to walk on a curve and his dog on another curve. Both the man and the dog are allowed to control their speed independently, but are not allowed to go backwards. Then, the Fréchet distance of the curves is the minimal length of a leash that is necessary.

# Algorithm Input Parameters

 P: A curve having two dimensional array of points
 
 Q: A curve having two dimensional array of points

# Algoithm Output Parameters
 
 The discrete Fréchet distance between curves 'P' and 'Q'.
 This algorithm also returns the co-ordinates of the curves 'P' and 'Q' respectively for which the Frechet Distance is taking place.

# Example Input

 p=[[0,0], [1,1], [2,5]]
 q=[[1,0],[2,1]]
 
 # Example Output
 
 Co-odinates:  [2. 5.] [2. 1.]
 Frechet distance: 4.0

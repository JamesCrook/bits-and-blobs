#Blending

 + X = A t + B * (1-t)
 
 equivalently 
 
 + X = B + (A - B) * t
 
 with one less multiplication.  Linear blend useful for vectors, colours 
 images etc.  Often better to specify a position as a blend rather than 
 'left-align', 'centre', 'right' - which correspond to 0, 0.5, 1.  Less
 code and more flexibility.
 
 Consider also Hermite blends.
 
 


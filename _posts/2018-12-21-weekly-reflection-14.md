---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---
Flag of Greece by Brandon Moctezuma



-  The country that I designed for is Greece 
-  The grade I expect to get is apprentice

## Current output

![Flag](/images/final-flag.png)



## Describe your process.
The help from my peers that helped me get to this point was put-image and define. This helped me get the code to layover other code to in the end form the flag to how it is. 


## Explain your code.

```
(put-image (rectangle 600 25 "solid" white)
                                280 48
(put-image (rectangle 300 25 "solid" white)
                                280 205
(put-image (rectangle 600 25 "solid" white)
                                280 103
(put-image (rectangle 300 25 "solid" white)
                                280 155
(put-image (rotate 90(rectangle 180 25 "solid" white))
                                65 205  
(put-image (rectangle 180 25 "solid" white)
                                40 180 
(put-image (square 180 "solid" "royalblue")
```

This piece of code is the base of the flag and the stripes which make it up.  Put-image helps the put an image into another image so that it can turn into the Greece Flag.

## Program code

```
(put-image (rectangle 600 25 "solid" white)
                                280 48
(put-image (rectangle 300 25 "solid" white)
                                280 205
(put-image (rectangle 600 25 "solid" white)
                                280 103
(put-image (rectangle 300 25 "solid" white)
                                280 155
(put-image (rotate 90(rectangle 180 25 "solid" white))
                                65 205  
(put-image (rectangle 180 25 "solid" white)
                                40 180
(put-image (square 180 "solid" "royalblue")
                                40 220
                                 (put-image (circle 0.11 "solid" white)
                                            77 80 
                                            (rectangle 385 245"solid" "royalblue")))))))))

(define white "whitesmoke" )
```

![Flag](/images/final-flag.png)

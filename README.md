# Symmetric Icon Attractor

## Equation
imgX <- imgX * X - imgY * Y  
imgY <- imgY * X + imgX * Y  
imgZ <- (a * (X * X + Y * Y) + e) + b * (imgX * X - imgY * Y)  
  
X <- imgZ * X - d * Y + c * imgX  
Y <- d * X + imgZ * Y - c * imgY  

## YouTube
https://www.youtube.com/watch?v=jJXn5HZPChI

## Image Sample
![Sample1](https://user-images.githubusercontent.com/36861752/85934737-5425a000-b922-11ea-953a-c980fad09958.png)

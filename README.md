# background-size: cover; issue with small images

This repository demonstrates a common issue encountered when using the `background-size: cover;` property in CSS. When the background image is smaller than the container element, it does not scale up to fill the container as expected. This results in a portion of the container being left unfilled.  The `bug.css` file contains the CSS code reproducing this error. The `bugSolution.css` file provides a solution. 

## Solution

The solution involves using `object-fit: cover;` within the background image. This allows the image to scale without breaking aspect ratio and ensuring the entire container is filled. 
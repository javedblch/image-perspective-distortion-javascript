# Image Perspective Distortion in JavaScript

This repository contains code examples and implementations of various techniques for creating image perspective distortion using JavaScript. The examples include Vanishing Point Perspective, Fish-Eye Perspective, and Stereographic Projection.

## Getting Started

To use the code in this repository, simply clone or download the project to your local machine. 

## Vanishing Point Perspective

Vanishing Point Perspective is a technique that simulates the perspective distortion caused by viewing an object from a particular angle. This effect is achieved by transforming the image so that all lines that are parallel in the original image converge to a single point in the transformed image.

To apply Vanishing Point Perspective to your own images, you can use the `applyVanishingPointPerspective()` function in the `vanishingPointPerspective.html` file. This function takes as input the image to be distorted, as well as the x and y coordinates of the vanishing point.

## Fish-Eye Perspective

Fish-Eye Perspective is a technique that simulates the distortion caused by viewing an object through a fish-eye lens. This effect is achieved by warping the image so that straight lines appear curved.

To apply Fish-Eye Perspective to your own images, you can use the `applyFishEyeEffect()` function in the `fishEyeEffect.html` file. This function takes as input the image to be distorted, as well as the strength of the fish-eye effect.

## Stereographic Projection

Stereographic Projection is a technique that maps points on a sphere to points on a plane. This effect is achieved by projecting the image onto a plane that is tangent to the sphere at a specific point.

To apply Stereographic Projection to your own images, you can use the `applyStereographicProjection()` function in the `stereographicProjection.html` file. This function takes as input the image to be distorted, as well as the distance from the center of projection.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.


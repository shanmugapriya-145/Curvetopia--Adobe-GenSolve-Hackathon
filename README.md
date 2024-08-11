# Curvetopia--Adobe-GenSolve-Hackathon

<h1>CURVETOPIA : Redefining the Art of Shape Identification</h1>
Welcome to Curvetopia, an innovative project developed for the Adobe Hackathon. Our mission is to transform the way we perceive and interpret shapes within 2D spaces, taking raster images and refining them into elegantly defined geometric structures. Utilizing advanced algorithms, This project aims to create precise representations of shapes using cubic Bezier curves.

<h2>Objective :</h2>
The goal of this project is to provide a complete pipeline that converts line art from raster PNG images into a series of structured curves. These curves are described as connected sequences of cubic Bezier curves, allowing for smooth and accurate representation. The project is divided into three core challenges:   

	1) Shape Regularization

	2)Symmetry Exploration

 	3)Curve Completion

<h1>Challenges</h1>

<h2>1. Shape Regularization:</h2>
   
In this challenge, we focus on recognizing and refining specific geometric shapes within a given set of curves. The process includes:

<h4>Straight Lines:</h4>

Detection and enhancement of linear segments.

<h4>Circular and Elliptical Forms: </h4>

Identification of curves that form circles or ellipses based on consistent radii or dual focal points.

<h4>Rectangular and Rounded Rectangular Structures:</h4>

Differentiation between straight-edged rectangles and those with curved edges.

<h4>Equilateral Polygons:</h4>

Recognition of polygons with equal sides and angles.

<h4>Stellar Patterns:</h4> 

Detection of star-like shapes with a central point and multiple outward radiating arms.

<h4>Activity:</h4>

This challenge primarily targets hand-drawn figures and doodles. The algorithm must discern which shapes can be regularized and which cannot. Test the algorithm with various images containing different geometric forms and verify the results.

<h2>2. Symmetry Exploration</h2>

This challenge addresses the identification of symmetrical properties in closed shapes. 

The key steps include:

<h4>Symmetry Detection:</h4>

Locating reflection symmetries that divide shapes into mirrored halves.

<h4>Bezier Curve Adaptation:</h4> 

Transforming shapes into point sets and fitting Bezier curves by identifying symmetrical properties.

<h2>3. Curve Completion</h2>

Here, we address the problem of completing curves that have undergone "planarization," where overlapping regions have been removed, leaving gaps. The task involves:

<h3>Shape Occlusion Levels:</h3>

<h2>Fully Enclosed:</h2>

For example, a circle entirely inside another.

<h2>Partially Enclosed: </h2>

For instance, a partially visible circle occluded by another.

<h2>Disconnected:</h2>

For example, a circle bisected by a rectangle, creating two separate segments.

<h3>Activity:</h3>

The focus is on completing the curves (not objects) using criteria such as smoothness, regularity, and symmetry to guide the algorithm.

In this repository , We have uploaded the problem statement , the dataset and the solution for the problem

<h1> Team Name -ShanSiv </h1>

<h3>Shanmugapriya.K - Github Id- shanmugapriya-145</h3>

<h3>Sivaranjani.R -Github Id - Sivaranjani09</h3>



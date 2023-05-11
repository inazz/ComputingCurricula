
# グラフィックスと視覚化 (GV)

Computer graphics is the term commonly used to describe the computer generation and
manipulation of images. It is the science of enabling visual communication through computation.
Its uses include cartoons, film special effects, video games, medical imaging, engineering, as
well as scientific, information, and knowledge visualization. Traditionally, graphics at the
undergraduate level has focused on rendering, linear algebra, and phenomenological approaches.
More recently, the focus has begun to include physics, numerical integration, scalability, and
special-purpose hardware. In order for students to become adept at the use and generation of
computer graphics, many implementation-specific issues must be addressed, such as file formats,
hardware interfaces, and application program interfaces. These issues change rapidly, and the
description that follows attempts to avoid being overly prescriptive about them. The area
encompassed by Graphics and Visualization is divided into several interrelated fields:

* Fundamentals: Computer graphics depends on an understanding of how humans use
vision to perceive information and how information can be rendered on a display device.
Every computer scientist should have some understanding of where and how graphics can
be appropriately applied as well as the fundamental processes involved in display
rendering.
* Modeling: Information to be displayed must be encoded in computer memory in some
form, often in the form of a mathematical specification of shape and form.
* Rendering: Rendering is the process of displaying the information contained in a model.
* Animation: Animation is the rendering in a manner that makes images appear to move
and the synthesis or acquisition of the time variations of models.
* Visualization: The field of visualization seeks to determine and present underlying
correlated structures and relationships in data sets from a wide variety of application
areas. The prime objective of the presentation should be to communicate the information
in a dataset so as to enhance understanding
* Computational Geometry: Computational Geometry is the study of algorithms that are
stated in terms of geometry.

Graphics and Visualization is related to machine vision and image processing, which are found
in the Intelligent Systems (IS) KA, and algorithms such as computational geometry, which are
found in the Algorithms and Complexity (AL) KA. Topics in virtual reality are found in the
Human-Computer Interaction (HCI) KA.

This description assumes students are familiar with fundamental concepts of data representation,
abstraction, and program implementation. 

**GV. グラフィックスと視覚化 (必修 2時間, 選択必修 1時間)**

| 知識単位 | 必修時間 | 選択必修時間 | 含選択科目 |
| -------- | -------- | ------------ | ---------- |
| GV/基礎概念                     | 2 | 1 | Y |
| GV/基本的なレンダリング         |   |   | Y |
| GV/幾何モデリング               |   |   | Y |
| GV/先進的なレンダリング         |   |   | Y |
| GV/コンピュータ・アニメーション |   |   | Y |
| GV/視覚化                       |   |   | Y |



## GV/基礎概念
*[必修 2 時間, 選択必修 1時間]*

For nearly every computer scientist and software developer, an understanding of how humans
interact with machines is essential. While these topics may be covered in a standard
undergraduate graphics course, they may also be covered in introductory computer science and
programming courses. Part of our motivation for including immediate and retained modes is that
these modes are analogous to polling vs. event driven programming. This is a fundamental
question in computer science: Is there a button object, or is there just the display of a button on
the screen? Note that most of the outcomes in this section are at the knowledge level, and many
of these topics are revisited in greater depth in later sections.

**トピック:**

[Core-Tier1]

* Media applications including user interfaces, audio and video editing, game engines, cad, visualization,
virtual reality
* Digitization of analog data, resolution, and the limits of human perception, e.g., pixels for visual display,
dots for laser printers, and samples for audio (HCI/Foundations)
* Use of standard APIs for the construction of UIs and display of standard media formats (see HCI/GUI
construction)
* Standard media formats, including lossless and lossy formats

[Core-Tier2]

* Additive and subtractive color models (CMYK and RGB) and why these provide a range of colors
* Tradeoffs between storing data and re-computing data as embodied by vector and raster representations of
images
* Animation as a sequence of still images

[Elective]

* Double buffering

**学習到達目標:**

[Core-Tier1]

1. Identify common uses of digital presentation to humans (e.g., computer graphics, sound). [Familiarity]
2. Explain in general terms how analog signals can be reasonably represented by discrete samples, for
example, how images can be represented by pixels. [Familiarity]
3. Explain how the limits of human perception affect choices about the digital representation of analog
signals. [Familiarity]
4. Construct a simple user interface using a standard API. [Usage]
5. Describe the differences between lossy and lossless image compression techniques, for example as
reflected in common graphics image file formats such as JPG, PNG, MP3, MP4, and GIF. [Familiarity]

[Core-Tier2]

6. Describe color models and their use in graphics display devices. [Familiarity]
7. Describe the tradeoffs between storing information vs. storing enough information to reproduce the
information, as in the difference between vector and raster rendering. [Familiarity]

[Elective]

8. Describe the basic process of producing continuous motion from a sequence of discrete frames (sometimes
called “flicker fusion”). [Familiarity]
9. Describe how double-buffering can remove flicker from animation. [Familiarity]



## GV/基本的なレンダリング
*[選択科目]*

This section describes basic rendering and fundamental graphics techniques that nearly every
undergraduate course in graphics will cover and that are essential for further study in graphics.
Sampling and anti-aliasing are related to the effect of digitization and appear in other areas of
computing, for example, in audio sampling.

**トピック:**

* Rendering in nature, e.g., the emission and scattering of light and its relation to numerical integration
* Forward and backward rendering (i.e., ray-casting and rasterization)
* Polygonal representation
* Basic radiometry, similar triangles, and projection model
* Affine and coordinate system transformations
* Ray tracing
* Visibility and occlusion, including solutions to this problem such as depth buffering, Painter’s algorithm,
and ray tracing
* The forward and backward rendering equation
* Simple triangle rasterization
* Rendering with a shader-based API
* Texture mapping, including minification and magnification (e.g., trilinear MIP-mapping)
* Application of spatial data structures to rendering
* Sampling and anti-aliasing
* Scene graphs and the graphics pipeline

**学習到達目標:**

1. Discuss the light transport problem and its relation to numerical integration i.e., light is emitted, scatters
around the scene, and is measured by the eye. [Familiarity]
2. Describe the basic graphics pipeline and how forward and backward rendering factor in this. [Familiarity]
3. Create a program to display 3D models of simple graphics images. [Usage]
4. Derive linear perspective from similar triangles by converting points (x, y, z) to points (x/z, y/z, 1). [Usage]
5. Obtain 2-dimensional and 3-dimensional points by applying affine transformations. [Usage]
6. Apply 3-dimensional coordinate system and the changes required to extend 2D transformation operations to
handle transformations in 3D. [Usage]
7. Contrast forward and backward rendering. [Assessment]
8. Explain the concept and applications of texture mapping, sampling, and anti-aliasing. [Familiarity]
9. Explain the ray tracing/rasterization duality for the visibility problem. [Familiarity]
10. Implement simple procedures that perform transformation and clipping operations on simple 2-dimensional
images. [Usage]
11. Implement a simple real-time renderer using a rasterization API (e.g., OpenGL) using vertex buffers and
shaders. [Usage]
12. Compare and contrast the different rendering techniques. [Assessment]
13. Compute space requirements based on resolution and color coding. [Assessment]
14. Compute time requirements based on refresh rates, rasterization techniques. [Assessment]



## GV/幾何モデリング
*[選択科目]*

**トピック:**

[Core-Tier1]

* Basic geometric operations such as intersection calculation and proximity tests
* Volumes, voxels, and point-based representations
* Parametric polynomial curves and surfaces
* Implicit representation of curves and surfaces
* Approximation techniques such as polynomial curves, Bezier curves, spline curves and surfaces, and nonuniform rational basis (NURB) spines, and level set method
* Surface representation techniques including tessellation, mesh representation, mesh fairing, and mesh
generation techniques such as Delaunay triangulation, marching cubes
* Spatial subdivision techniques
* Procedural models such as fractals, generative modeling, and L-systems
* Graftals, cross referenced with programming languages (grammars to generated pictures)
* Elastically deformable and freeform deformable models
* Subdivision surfaces
* Multiresolution modeling
* Reconstruction
* Constructive Solid Geometry (CSG) representation

**学習到達目標:**

1. Represent curves and surfaces using both implicit and parametric forms. [Usage]
2. Create simple polyhedral models by surface tessellation. [Usage]
3. Generate a mesh representation from an implicit surface. [Usage]
4. Generate a fractal model or terrain using a procedural method. [Usage]
5. Generate a mesh from data points acquired with a laser scanner. [Usage]
6. Construct CSG models from simple primitives, such as cubes and quadric surfaces. [Usage]
7. Contrast modeling approaches with respect to space and time complexity and quality of image.
[Assessment]



## GV/先進的なレンダリング
*[選択科目]*

**トピック:**

* Solutions and approximations to the rendering equation, for example:
 * Distribution ray tracing and path tracing
 * Photon mapping
 * Bidirectional path tracing
 * Reyes (micropolygon) rendering
 * Metropolis light transport
* Time (motion blur), lens position (focus), and continuous frequency (color) and their impact on rendering
* Shadow mapping
* Occlusion culling
* Bidirectional Scattering Distribution function (BSDF) theory and microfacets
* Subsurface scattering
* Area light sources
* Hierarchical depth buffering
* The Light Field, image-based rendering
* Non-photorealistic rendering
* GPU architecture
* Human visual systems including adaptation to light, sensitivity to noise, and flicker fusion


**学習到達目標:**

1. Demonstrate how an algorithm estimates a solution to the rendering equation. [Assessment]
2. Prove the properties of a rendering algorithm, e.g., complete, consistent, and unbiased. [Assessment]
3. Analyze the bandwidth and computation demands of a simple algorithm. [Assessment]
4. Implement a non-trivial shading algorithm (e.g., toon shading, cascaded shadow maps) under a rasterization
API. [Usage]
5. Discuss how a particular artistic technique might be implemented in a renderer. [Familiarity]
6. Explain how to recognize the graphics techniques used to create a particular image. [Familiarity]
7. Implement any of the specified graphics techniques using a primitive graphics system at the individual
pixel level. [Usage]
8. Implement a ray tracer for scenes using a simple (e.g., Phong model) BRDF plus reflection and refraction.
[Usage]



## GV/コンピュータ・アニメーション
*[選択科目]*

**トピック:**

* Forward and inverse kinematics
* Collision detection and response
* Procedural animation using noise, rules (boids/crowds), and particle systems
* Skinning algorithms
* Physics based motions including rigid body dynamics, physical particle systems, mass-spring networks for
cloth and flesh and hair
* Key-frame animation
* Splines
* Data structures for rotations, such as quaternions
* Camera animation
* Motion capture

**学習到達目標:**

1. Compute the location and orientation of model parts using a forward kinematic approach. [Usage]
2. Compute the orientation of articulated parts of a model from a location and orientation using an inverse
kinematic approach. [Usage]
3. Describe the tradeoffs in different representations of rotations. [Assessment]
4. Implement the spline interpolation method for producing in-between positions and orientations. [Usage]
5. Implement algorithms for physical modeling of particle dynamics using simple Newtonian mechanics, for
example Witkin & Kass, snakes and worms, symplectic Euler, Stormer/Verlet, or midpoint Euler methods.
[Usage]
6. Discuss the basic ideas behind some methods for fluid dynamics for modeling ballistic trajectories, for
example for splashes, dust, fire, or smoke. [Familiarity]
7. Use common animation software to construct simple organic forms using metaball and skeleton. [Usage]



## GV/視覚化
*[選択科目]*

Visualization has strong ties to the Human-Computer Interaction (HCI) knowledge area as well
as Computational Science (CN). Readers should refer to the HCI and CN KAs for additional
topics related to user population and interface evaluations.

**トピック:**

* Visualization of 2D/3D scalar fields: color mapping, isosurfaces
* Direct volume data rendering: ray-casting, transfer functions, segmentation
* Visualization of:
 * Vector fields and flow data
 * Time-varying data
 * High-dimensional data: dimension reduction, parallel coordinates,
 * Non-spatial data: multi-variate, tree/graph structured, text
* Perceptual and cognitive foundations that drive visual abstractions
* Visualization design
* Evaluation of visualization methods
* Applications of visualization



**学習到達目標:**

1. Describe the basic algorithms for scalar and vector visualization. [Familiarity]
2. Describe the tradeoffs of visualization algorithms in terms of accuracy and performance. [Assessment]
3. Propose a suitable visualization design for a particular combination of data characteristics and application
tasks. [Assessment]
4. Analyze the effectiveness of a given visualization for a particular task. [Assessment]
5. Design a process to evaluate the utility of a visualization algorithm or system. [Assessment]
6. Recognize a variety of applications of visualization including representations of scientific, medical, and
mathematical data; flow visualization; and spatial analysis. [Familiarity]

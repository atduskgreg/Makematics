---
layout: page
title: "Research"
---
{% include JB/setup %}

## Academic Papers

_This section lists academic papers that describe techniques we'd like to implement in code. These can range from artistic effects in computer graphics to novel 3D scanning or computer vision approaches to ways of processing or generating 3D geometry for fabrication. Each entry includes a brief description of the technique and links to a page with more details. Those pages will act as a working area to understand and explain the technique as well as including links to code that implements it. If you would like to participate in breaking down or implementing any paper, please do so. Participation is highly welcome._

### [Depth from Focus/Defocus](/research/dfd)

![Depth from focus/defocus](http://homepages.inf.ed.ac.uk/rbf/CVonline/LOCAL_COPIES/FAVARO1/geometry.jpg)

_This research describes a method for extracting 3D geometry from a series of images with different focal depths of the same scene. It seems especially promising given the availability of the [Lytro](http://www.lytro.com/) camera that can adjust focus after the taking of a photograph._

### [Computer-Generated Watercolor](/research/watercolor)

![simulated watercolor](/assets/images/simulated_watercolor.png)

_This paper describes a way to create realistic watercolor effects by simulating the interaction of water, pigment, and paper. It uses a cellular automata-based system as well as a model of the flow of water to emulate how watercolor distributes pigment as it is absorbed by paper. The authors include detailed pseudocode of the algorithms involved. The mathematical level involved appears to be some mild vector calculus._

### [Pose from Orthography and Scaling with Iterations (POSIT)](/research/posit)

_This is a technique for estimating the pose of an object from a single image. It has promising applications for augmented reality amongst other areas. The original paper has an implementation in Mathematica and there's a link to a Willow Garage page that summarizes an implementation in OpenCV and OpenGL._

### [Screen Space Ambient Occlusion](/research/ssao)

![screen space ambient occlusion](http://upload.wikimedia.org/wikipedia/commons/8/8b/Screen_space_ambient_occlusion.jpg)

_This is a technique that produces realistic lighting and reflection in 3D renders in real time. It is implemented in a pixel shader. There is working, but messy, OpenFrameworks code._

### [Random Sample Consensus (RANSAC)](/research/ransac)

![RANSAC plane fitting](http://www.mrpt.org/sites/default/files/images/Ransac_example_3D_plane_0.png)

_RANSAC is an method for fitting lines and planes to observed data. In a world with a lot of point clouds, it seems like it might be useful for extracting simplified geometry from rich but noisy 3D scans. There are a number of viable implementations around including a partial one in OpenFrameworks._

### [GigaVoxels](/research/gigavoxels)

<iframe width="420" height="315" src="http://www.youtube.com/embed/HScYuRhgEJw" frameborder="0" allowfullscreen></iframe>

_This is a very sophisticated technique for rendering large volumetric data sets. It can display billions of voxels in real time._

### [Mipmapping](/research/mipmapping)

![Mipmapping texture](http://upload.wikimedia.org/wikipedia/commons/5/5c/MipMap_Example_STS101.jpg)

_This is a technique for combining multiple sizes of the same texture to do efficient rendering at multiple levels of detail from way zoomed out to up-close._

## Math Concepts

_This section lists mathematical techniques and terms that show up repeatedly in the academic papers above. Understanding and implementing those papers require a working knowledge of these techniques and how to turn them into code. The pages linked here will act as a working area to understand these mathematical concepts and to learn how to work with them in code._

### [Euler Angles](/research/euler_angles)

### [Quaternions](/research/quaternions)

### [Laplacian](/research/laplacian)

### [Normals and Cross Products](/research/normals)

### [Gaussian Function](/research/gaussian)

### [Kalman Filters](/research/kalman)


## Programming Techniques

_This section lists programming techniques that are needed to implement the ideas and algorithms in the academic papers listed above. To turn the ideas in these papers into practical code often involves learning to write code that uses some of the advanced features of modern graphics programming. The pages linked from this section will act as a working area to understand these features and how to use them in practice. Where possible they will include examples in as many languages as possible. Contributions welcome._

### Frame Buffer Objects (FBOs)

### Pixel Shaders

### Vertex Shaders

### Geometry Shaders

### Vertex Buffer Objects (VBOs)
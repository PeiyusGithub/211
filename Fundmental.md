#### Fundamentals data
**Sampling**

Sampling: Uniform vs Non-uniform 

Reconstruction: discrete -> continuous

Aliasing: incorrect reconstruction

Nyquist Sampling Rate:  
By sampling at least **twice** the frequency (2 samples per cycle), signal can be reconstructed correctly.

**QUantization**

Making continuous(analog) signal to digital signal.

**Representation**  
Frequency domain representation:   
A signal is a linear combination of sine or cosine waves

Explicit Representation: y = ax + b  
Implicit Representation: ax + by + c = 0

Discrete Representation: A 3D cube defined by a set of quadrilaterals or triangles is called **Mesh**  
The entities that make up the mesh (e.g. lines, triangles or quadrilaterals) are called the **primitives**. 

**Manifold Definitions**

• Manifold  
 Every edge has exactly two incident triangles.  
• Manifolds with boundaries  
 Every edge has either one or two incident triangles.  
• Non-manifold  
 Not with above restrictions.  
 
 **Euler Characteristic**
 
 e = V-E+F (V: Vertices, E: Edges, F: Faces).   
 
 Changing geometric properties keeps Euler characteristic invariant. Such as adding edges, vertices 
 
 **Genus**
 
 Native: Number of handles  
 e = 2- 2g  
 
 
 **Noise**  
 Random noise:  Addition of random values at random locations in the data.   
 Outlier noise: can be solved by Median filter
 
 
 #### Interpolation
 Estimate function for values which it has not been measured.
 
 Linear interpolation:  
Assuming a line between samples.  
Change abruptly at sample points  
C0 continuity  
V on the line segment V1 V2:   
V = aV1 + (1 - a)V2 0 <= a <= 1


Non-linear interpolation:  
A smooth curve passes through samples  
First derivative continuous -C1 continuous  
Second derivative continuous - C2 continuous   
 
 
Bilinear Interpolation  
• 2D Data  
• Interpolating in one direction followed by interpolating in the second direction.
![](https://i.imgur.com/SNgnctO.png)